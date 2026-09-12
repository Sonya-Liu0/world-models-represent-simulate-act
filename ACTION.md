# 行动与控制 (Action)

[返回首页 / Home](README.md) · [完整列表 / All Papers](WORLD_MODELS.md)

## 目录 (Contents)

- [1. 策略落地与具身控制 (Policy Grounding & Embodied Control)](#section-1)
- [2. 视觉语言动作模型 (Vision-Language-Action Models)](#section-2)
- [3. 世界动作模型 (World Action Models)](#section-3)

<a id="section-1"></a>

## 1. 策略落地与具身控制 (Policy Grounding & Embodied Control)

### Improving vision-and-language navigation with image-text pairs from the web (2020)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2004.14973)
- Code: [官方代码](https://github.com/arjunmajum/vln-bert)
- Code Notes: 原论文作者的 VLN-BERT 训练和评测代码。
- Summary: VLN-BERT grounds web-pretrained vision-language representations in navigation decisions.

### CLIPort: what and where pathways for robotic manipulation (2021)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v164/shridhar22a.html)
- Code: [GitHub](https://github.com/cliport/cliport)
- Summary: CLIPort maps language-conditioned visual features to manipulation actions.

### Do as I can, not as I say: grounding language in robotic affordances (2022)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2204.01691)
- Code: [官方代码（部分发布）](https://github.com/google-research/google-research/tree/master/saycan)
- Code Notes: 官方桌面仿真 notebook；不是论文完整真实机器人系统。
- Summary: SayCan grounds language-model plans in feasible robot skills and value functions.

### RT-1: robotics transformer for real-world control at scale (2023)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2212.06817)
- Code: [官方代码](https://github.com/google-research/robotics_transformer)
- Code Notes: 官方 RT-1 模型组件、测试与检查点。
- Summary: RT-1 scales observation-to-action mapping for real-world robot control.

### A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2601.14628)
- Code: [官方代码](https://github.com/guoweiyu/NeuroVLA)
- Code Notes: 作者 NeuroVLA 仓库，标题和作者与论文对应。
- Summary: Focuses on fast reflexive embodied control rather than standalone representation or generation.

### PaLM-E: an embodied multimodal language model (2023)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v202/driess23a.html)
- Code: 待补充（官方实现未确认；有社区架构实现）
- Project: [官方项目页](https://palm-e.github.io/)
- Community Code: [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E)
- Code Notes: 社区仓库 README 明确说明仅有架构、无预训练权重和 tokenizer。不能据此声称可直接运行原版 PaLM-E 或复现论文结果。
- Summary: PaLM-E grounds multimodal language representations in embodied tasks and action-oriented reasoning.


<a id="section-2"></a>

## 2. 视觉语言动作模型 (Vision-Language-Action Models)

### rt-2: vision-language-action models transfer web knowledge to robotic control (2023)

- Paper: [论文 / Resource](https://arxiv.org/abs/2307.15818)
- Code: 待补充（官方实现未确认；有社区实现）
- Project: [官方项目页](https://robotics-transformer2.github.io/)
- Community Code: [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2)
- Code Notes: 社区仓库作者声明为个人实现，不能视为 Google 原版 RT-2；未验证论文结果、动作解码及真实机器人执行能力。
- Summary: Transfers web-scale vision-language knowledge into executable robot actions; the main contribution is an embodied VLA policy.

### unified vision-language-action model (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2506.19850)
- Code: [官方代码](https://github.com/baaivision/UniVLA)
- Code Notes: 引用编号为 2506.19850，避免与其他同名 UniVLA 仓库混淆。
- Summary: Unifies visual, language, and action generation in one policy model.

### OpenVLA: an open-source vision-language-action model (2024)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v270/kim25c.html)
- Code: [GitHub](https://github.com/openvla/openvla)
- Summary: OpenVLA is an open-source vision-language-action policy.

### $pi_0$: a vision-language-action flow model for general robot control (2024)

- Paper: [论文 / Resource](https://arxiv.org/abs/2410.24164)
- Code: [官方代码](https://github.com/Physical-Intelligence/openpi)
- Code Notes: 官方 openpi，共享训练、微调与推理仓库。
- Summary: Pi-zero generates continuous robot actions with a vision-language-action flow model.

### $pi_0.5$: a vision-language-action model with open-world generalization (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2504.16054)
- Code: [官方代码](https://github.com/Physical-Intelligence/openpi)
- Code Notes: 官方 openpi；README 明确支持 π0.5，目前支持 flow-matching head。
- Summary: Pi-0.5 extends VLA control toward open-world generalization.

### GR00T N1: an open foundation model for generalist humanoid robots (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2503.14734)
- Code: [官方代码](https://github.com/NVIDIA/Isaac-GR00T)
- Code Notes: 官方 GR00T 系列仓库；主分支已迭代，复现 N1 应使用对应历史版本与权重。
- Summary: GR00T N1 is a generalist humanoid foundation policy connecting multimodal perception to control.

### Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2502.19645)
- Code: [官方代码](https://github.com/moojink/openvla-oft)
- Code Notes: OpenVLA-OFT 官方训练、微调与评测实现。
- Summary: Studies efficient fine-tuning of VLA policies for speed and task success.


### EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2602.16710)
- Code: 待发布（官方页面标注 Coming Soon）
- Project: [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/)
- Code Notes: 官方页面仍标注 GitHub (Coming Soon!)。EgoScale 是从人类视频向机器人迁移的 VLA 学习方法，已从数据集分类移到行动 / VLA；后续 GR00T 使用相关数据不等于原论文完整实现已发布。
- Summary: EgoScale pretrains a VLA model on large-scale egocentric human videos and transfers dexterous manipulation skills to robots through aligned human–robot training.

<a id="section-3"></a>

## 3. 世界动作模型 (World Action Models)

### DreamDojo: a generalist robot world model from large-scale human videos (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2602.06949)
- Code: [官方代码](https://github.com/NVIDIA/DreamDojo)
- Code Notes: 官方预训练、后训练、蒸馏和评测代码。
- Summary: DreamDojo learns a robot world model from large-scale human videos and uses predictions for embodied behavior.

### Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2512.03044)
- Code: [官方代码（部分发布）](https://github.com/jiayueru/Video2Act)
- Code Notes: 作者发布的 RoboTwin 2.0 策略实现；仓库明确不包含模型检查点和数据。
- Summary: Video2Act uses video diffusion and predicted motion structure to produce robot actions.

### World action models are zero-shot policies (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2602.15922)
- Code: [官方代码](https://github.com/dreamzero0/dreamzero)
- Code Notes: DreamZero 官方项目页直接链接的预训练、微调与评测仓库。
- Summary: Explicitly formulates world action models as zero-shot policies.

### MotuBrain: an advanced world action model for robot control (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2604.27792)
- Code: 待补充（官方仓库已建，未发现模型源码）
- Repository: [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain)
- Related Code: [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM)
- Code Notes: 本轮复查仍只见报告、展示材料和许可文件。minWM 是同机构公开的世界模型教程框架，与 MotuBrain 是不同项目。
- Summary: MotuBrain is explicitly designed as a world action model for robot control.
