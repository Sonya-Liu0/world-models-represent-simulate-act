# 世界模型文献库：Represent、Simulate 与 Action

本仓库依据综述 **Learning to Represent, Simulate, and Act: A Survey of World Models** 及配套参考文献整理，目标是形成一个可复现、可扩展的世界模型文献库。

## 当前内容

- 共整理 **64 条参考文献记录**；原始 BibTeX 中缺少编号 `56`。
- 核心方法论文按主要贡献分为：**Represent 10 篇、Simulate 13 篇、Action 16 篇**。
- 另有 **Supporting 25 条**，用于保存综述、理论、数据集、基准、指标、仿真器与报告，避免将非模型论文强行塞入三类。
- 当前目录提供 **59 个可自动下载的 PDF 来源**；其余为网页、报告或待核验记录。
- 每条记录均包含主分类、次分类、分类理由、下载地址、目标路径与元数据质量标记。

## 三类划分原则

- **Represent**：主要创新位于预测表征、潜状态、视觉/多模态 token、对象结构、场景图或三维几何表示。
- **Simulate**：主要创新位于潜空间滚动、未来观测生成、交互世界生成或物理一致性模拟。
- **Action**：主要创新位于策略落地、VLA 动作生成、预测引导控制或 World Action Model。

对于同时跨越多个环节的方法，仓库保留一个便于浏览的 `primary_category`，并用 `secondary_categories` 标记交叉属性。

## 下载全部可用论文

```bash
python -m pip install -r requirements.txt
python scripts/download_papers.py --all --workers 4
```

只下载某一类：

```bash
python scripts/download_papers.py --category represent
python scripts/download_papers.py --category simulate
python scripts/download_papers.py --category action
```

下载器会检查 PDF 文件头、跳过已下载文件、计算 SHA-256，并生成下载清单与报告。论文 PDF 默认不提交到 Git，以避免仓库过大并降低第三方版权风险。

## 维护分类目录

`data/papers.yaml` 是唯一需要人工维护的主目录。修改后执行：

```bash
python scripts/validate_catalog.py
python scripts/export_catalog.py
python scripts/make_reading_list.py
```

## 发布到 GitHub

完成 GitHub CLI 登录后，在仓库目录运行：

```bash
gh auth login
bash scripts/publish_github.sh world-models-represent-simulate-act public
```

将最后一个参数改为 `private` 可创建私有仓库。

## 重要元数据说明

原始参考文献中存在少量缺失或冲突。仓库不会对不确定来源进行猜测下载；详细记录见 `docs/metadata-audit.md`。其中编号 `4` 的给定 arXiv 标识实际指向另一篇论文，因此已被明确阻止自动下载，等待补充正确文献信息。
