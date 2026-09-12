# 贡献指南 / Contributing

## 添加或修改条目

1. 根据主要贡献，在 REPRESENT.md、SIMULATE.md、ACTION.md、SURVEY.md、DATASETS.md 或 BENCHMARKS.md 中选择一个主类。
2. 在对应小节添加条目，并同步 WORLD_MODELS.md；新增条目时更新两份 README 的资源数量。
3. 优先使用作者、出版社或官方项目提供的论文、代码和项目链接。没有可靠链接时填写“待补充”，不要猜测。
4. 核对标题、年份、重复条目和目录跳转。

```markdown
### Paper Title (Year)

- Paper: [论文](https://...)
- Code: [GitHub](https://...)
- Summary: One sentence describing the contribution.
```

## 分类原则

- Represent：预测表征、多模态词元、物体/场景结构。
- Simulate：潜在动力学、未来生成、交互环境和三维世界生成。
- Act：策略、VLA 和预测驱动的行动模型。
- 综述、数据集、评测和工具分别归入支持资源页面。

同一条目只在一个主类完整收录。主类按主要技术贡献确定，而不是仅根据是否包含机器人实验或视频输出。

## 链接与发布状态

- Code：优先链接原论文作者/机构发布的实现；部分代码公开时注明范围。
- Community Code：社区复现单列，说明是否只有架构、是否缺少权重，以及未经验证的范围。
- Related Code：相关独立项目，不得当作原论文代码。
- Repository / Data / Video / API：分别用于综述资料、数据、演讲和服务入口。
- 待补充：未找到可确认的原论文官方实现；不等于确定没有代码。
- 待发布：仅在官方明确写 Coming Soon 或相同含义时使用。
- 不适用：演讲等没有独立实现要求的资源。

核查时记录日期、标题/论文编号对应关系和来源；同步分类页、WORLD_MODELS.md 与 CODE_LINK_AUDIT.md。新增或改动社区实现时，同步 RESOURCE_STATUS.md 中的范围说明。不要把 API、仓库占位页或另一个模型的实现标成原模型源码。
