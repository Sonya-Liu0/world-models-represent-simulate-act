# Awesome World Models: Represent, Simulate, and Act 🌍

整理世界模型相关论文与资源，围绕 **表征（Represent）→ 模拟（Simulate）→ 行动（Act）** 展开。

A curated collection of world model papers and resources organized by Representation, Simulation, and Action.

欢迎 Star、Fork 和 PR，一起补充论文、代码与项目链接。

## 论文目录 (Contents)

**[📚 浏览完整论文列表：64 条去重资源](WORLD_MODELS.md)**

- [1. 表征学习 (Representation)](REPRESENT.md)
  - [1.1. 潜在状态与预测表征 (Latent & Predictive Representations)](REPRESENT.md#section-1)
  - [1.2. 多模态词元表征 (Multimodal Tokenization)](REPRESENT.md#section-2)
  - [1.3. 结构化世界表征 (Structured Representations)](REPRESENT.md#section-3)
- [2. 世界模拟 (Simulation)](SIMULATE.md)
  - [2.1. 潜在动力学 (Latent Dynamics)](SIMULATE.md#section-1)
  - [2.2. 视频与交互生成 (Video & Interactive Generation)](SIMULATE.md#section-2)
  - [2.3. 三维世界与数据生成 (3D Worlds & Data Generation)](SIMULATE.md#section-3)
- [3. 行动与控制 (Action)](ACTION.md)
  - [3.1. 策略落地与具身控制 (Policy Grounding & Embodied Control)](ACTION.md#section-1)
  - [3.2. 视觉语言动作模型 (Vision-Language-Action Models)](ACTION.md#section-2)
  - [3.3. 世界动作模型 (World Action Models)](ACTION.md#section-3)
- [4. 综述与基础 (Surveys & Foundations)](SURVEY.md)
  - [4.1. 综述 (Surveys)](SURVEY.md#section-1)
  - [4.2. 理论与报告 (Theory & Talks)](SURVEY.md#section-2)
  - [4.3. 其他相关系统 (Related Systems)](SURVEY.md#section-3)
- [5. 数据集与采集工具 (Datasets & Collection)](DATASETS.md)
  - [5.1. 数据集 (Datasets)](DATASETS.md#section-1)
  - [5.2. 数据采集接口 (Data Collection Interfaces)](DATASETS.md#section-2)
- [6. 评测与仿真工具 (Benchmarks & Simulators)](BENCHMARKS.md)
  - [6.1. 评测基准 (Benchmarks)](BENCHMARKS.md#section-1)
  - [6.2. 评测指标 (Metrics)](BENCHMARKS.md#section-2)
  - [6.3. 物理仿真器 (Physics Simulators)](BENCHMARKS.md#section-3)

## 阅读说明

- 每条资源采用“论文标题 + Paper + Code + Summary”格式。
- 按原条目的 Category 归入一个主类；跨方向工作可通过完整列表搜索。
- 当前收录 64 条去重资源，包含论文、报告、数据集和工具，并非全部都是世界模型方法论文。
- 标题、年份、论文链接和摘要沿用原目录，尚未逐篇核验；缺失链接标为“待补充”。

## 代码链接核查

已检索原先缺失的 56 条资源：补充 34 条官方实现链接（含 3 条部分发布）、5 条官方工具/基线入口、4 条综述资料库和 1 条数据入口；上一轮剩余 12 条现已细分为 10 条官方实现待确认/待发布，以及 2 条代码不适用的演讲。

[查看全部 56 条缺失项与检索结果](CODE_LINK_AUDIT.md)。未确认的代码继续保留状态；新增 4 条社区实现及 2 条相关独立项目作为补充，均注明归属和限制。存在公开仓库不代表完整训练代码、模型权重和数据均已发布。

[查看 12 条资源的进一步完善结果](RESOURCE_STATUS.md)。EgoScale 已按方法性质归入行动 / VLA，两个报告条目已补齐可核验来源。

## 参与贡献 (Contributing)

请参阅 [贡献指南](CONTRIBUTING.md)。

## 相关综述 (Related Survey)

Learning to Represent, Simulate, and Act: A Survey of World Models

## 排版参考 (Format Reference)

列表排版参考 [Awesome-CVPR2024-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-CVPR2026-CVPR2025-CVPR2024-CVPR2021-CVPR2020-Low-Level-Vision/blob/master/CVPR2024.md)，论文内容来自本仓库已有目录。

## License

参见 [LICENSE](LICENSE)。论文版权归各自作者和出版方所有。
