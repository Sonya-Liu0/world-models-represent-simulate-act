# 12 条未确认官方代码资源的进一步完善

核查日期：2026-09-12。这里保留上一轮的 12 条追踪对象，并区分资源性质。尚未确认的实现仍保留待补充/待发布状态。

## 状态速查

| 条目 | 官方实现状态 | 新增可用入口 |
|---|---|---|
| Embodied semantic scene graph generation (2021) | 待补充（未找到可确认的原论文实现） | [出版页面](https://proceedings.mlr.press/v164/li22e.html) |
| Learning interactive world model for object-centric reinforcement learning (2025) | 待补充（已找到项目页，未发现代码入口） | [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm) |
| video generation models as world simulators (2024) | 待补充（未确认 Sora 原模型官方实现） | [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/) · [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora) |
| genie: generative interactive environments (2024) | 待补充（官方实现未确认；有社区实现） | [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/) · [Open-Genie（非官方）](https://github.com/myscience/open-genie) |
| marble: generative multimodal 3d world model (2025) | 待补充（模型源码未确认；已提供官方 API） | [Marble 官方文档](https://docs.worldlabs.ai/) · [World API Quickstart](https://docs.worldlabs.ai/api) |
| PaLM-E: an embodied multimodal language model (2023) | 待补充（官方实现未确认；有社区架构实现） | [官方项目页](https://palm-e.github.io/) · [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E) |
| rt-2: vision-language-action models transfer web knowledge to robotic control (2023) | 待补充（官方实现未确认；有社区实现） | [官方项目页](https://robotics-transformer2.github.io/) · [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2) |
| MotuBrain: an advanced world action model for robot control (2026) | 待补充（官方仓库已建，未发现模型源码） | [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain) · [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM) |
| Predictive Learning (2016) | 不适用（邀请报告，不是独立代码项目） | [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning) |
| the information bottleneck method (2000) | 待补充（原作者实现未确认；有社区实现） | [原论文](https://arxiv.org/abs/physics/0004057) · [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck) |
| Robotics' End Game: Nvidia's Jim Fan (2026) | 不适用（会议演讲，不是独立代码项目） | [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs) |
| EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026) | 待发布（官方页面标注 Coming Soon） | [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/) |

## 逐项说明

### 1. Embodied semantic scene graph generation (2021)

继续按完整标题和作者核查，仍未发现可靠代码链接。CoRL 2021 会议论文于 PMLR 2022 出版，保留原目录会议年份。

- Project / Source: [出版页面](https://proceedings.mlr.press/v164/li22e.html)

### 2. Learning interactive world model for object-centric reinforcement learning (2025)

新增 FIOC-WM 项目页；页面含方法和结果展示，当前未提供公开代码链接。

- Project: [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm)

### 3. video generation models as world simulators (2024)

Open-Sora 是独立视频生成项目，只作为相关开放研究入口；不代表 OpenAI Sora 源码或原报告复现。

- Project / Source: [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/)
- Related Code: [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora)

### 4. genie: generative interactive environments (2024)

Open-Genie 明确声明非官方，提供视频 tokenizer、latent action 和 dynamics 训练入口；尚未验证其训练结果与原论文一致。

- Project: [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/)
- Community Code: [Open-Genie（非官方）](https://github.com/myscience/open-genie)

### 5. marble: generative multimodal 3d world model (2025)

可通过 World API 调用服务；接口调用示例不等于 Marble 模型源码或可本地运行的权重。

- Project: [Marble 官方文档](https://docs.worldlabs.ai/)
- API: [World API Quickstart](https://docs.worldlabs.ai/api)

### 6. PaLM-E: an embodied multimodal language model (2023)

社区仓库 README 明确说明仅有架构、无预训练权重和 tokenizer。不能据此声称可直接运行原版 PaLM-E 或复现论文结果。

- Project: [官方项目页](https://palm-e.github.io/)
- Community Code: [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E)

### 7. rt-2: vision-language-action models transfer web knowledge to robotic control (2023)

社区仓库作者声明为个人实现，不能视为 Google 原版 RT-2；未验证论文结果、动作解码及真实机器人执行能力。

- Project: [官方项目页](https://robotics-transformer2.github.io/)
- Community Code: [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2)

### 8. MotuBrain: an advanced world action model for robot control (2026)

本轮复查仍只见报告、展示材料和许可文件。minWM 是同机构公开的世界模型教程框架，与 MotuBrain 是不同项目。

- Repository: [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain)
- Related Code: [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM)

### 9. Predictive Learning (2016)

原目录的 “the cake and the cherry” 是概念性条目名，现按可核验的报告名称 Predictive Learning 整理。报告由 Yann LeCun 于 NIPS 2016 发表；录像页面上传于 2017，不能误作报告年份。未核验该比喻在录像中的时间戳。

- Video: [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning)

### 10. the information bottleneck method (2000)

社区 Python 实现对应 Tishby 等人的 Information Bottleneck 方法；作者并非原论文署名作者。未确认仓库许可证，不将公开可见等同于已授权开源。论文会议版本为 1999，当前条目保留 arXiv 2000 年份。

- Project / Source: [原论文](https://arxiv.org/abs/physics/0004057)
- Community Code: [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck)

### 11. Robotics' End Game: Nvidia's Jim Fan (2026)

已补齐 Sequoia Capital 主办方录像，发布于 2026-04-30。演讲所述模型应分别查阅对应论文条目的代码。

- Video: [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs)

### 12. EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)

官方页面仍标注 GitHub (Coming Soon!)。EgoScale 是从人类视频向机器人迁移的 VLA 学习方法，已从数据集分类移到行动 / VLA；后续 GR00T 使用相关数据不等于原论文完整实现已发布。

- Project: [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/)

## 阅读社区代码前需要了解的范围

- Open-Genie：作者标注 unofficial；有模型组件和训练入口，未验证复现实验结果。
- PALM-E：仓库明确仅有架构，缺少 tokenizer 和预训练权重。
- RT-2：个人实现，未验证原论文的模型行为、实验指标或机器人执行流程。
- Information Bottleneck：提供方法实现，但仓库许可未确认；只登记为公开社区代码参考。
- Open-Sora、minWM：相关独立项目，不是 Sora、MotuBrain 的官方实现。

## 元数据修正

- “the cake and the cherry” 改为可核验的报告名称 Predictive Learning (2016)，保留原标签的说明。未给未经核验的视频时间戳。
- Robotics' End Game 补齐完整标题及 Sequoia Capital 主办方录像。
- EgoScale 是人类视频到机器人迁移的 VLA 方法，移入 ACTION.md 的 VLA 小节；不能将它等同于一个已公开数据集。
- Embodied Semantic Scene Graph Generation 保留 CoRL 2021 年份，并说明论文集在 2022 年出版。

[返回完整列表](WORLD_MODELS.md) · [查看全部 56 条核查记录](CODE_LINK_AUDIT.md)
