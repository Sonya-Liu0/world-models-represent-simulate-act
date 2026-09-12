# Awesome World Models: Represent, Simulate, and Act 🌍

世界模型论文与资源列表，按 **表征 → 模拟 → 行动** 组织，并单列综述、数据集与评测工具。

标题、年份和摘要沿用原目录；代码与资源链接于 2026-09-12 逐项检索。代码、部分发布、官方工具及综述资料分别标注；“待补充”表示本次未确认官方公开实现，不代表确定没有开源。完整检索记录见 [代码补充核查清单](CODE_LINK_AUDIT.md)。

## 目录 (Contents)

- [1. 表征学习 (Representation)](#topic-1)
  - [1.1. 潜在状态与预测表征 (Latent & Predictive Representations)](#topic-1-1)
  - [1.2. 多模态词元表征 (Multimodal Tokenization)](#topic-1-2)
  - [1.3. 结构化世界表征 (Structured Representations)](#topic-1-3)
- [2. 世界模拟 (Simulation)](#topic-2)
  - [2.1. 潜在动力学 (Latent Dynamics)](#topic-2-1)
  - [2.2. 视频与交互生成 (Video & Interactive Generation)](#topic-2-2)
  - [2.3. 三维世界与数据生成 (3D Worlds & Data Generation)](#topic-2-3)
- [3. 行动与控制 (Action)](#topic-3)
  - [3.1. 策略落地与具身控制 (Policy Grounding & Embodied Control)](#topic-3-1)
  - [3.2. 视觉语言动作模型 (Vision-Language-Action Models)](#topic-3-2)
  - [3.3. 世界动作模型 (World Action Models)](#topic-3-3)
- [4. 综述与基础 (Surveys & Foundations)](#topic-4)
  - [4.1. 综述 (Surveys)](#topic-4-1)
  - [4.2. 理论与报告 (Theory & Talks)](#topic-4-2)
  - [4.3. 其他相关系统 (Related Systems)](#topic-4-3)
- [5. 数据集与采集工具 (Datasets & Collection)](#topic-5)
  - [5.1. 数据集 (Datasets)](#topic-5-1)
  - [5.2. 数据采集接口 (Data Collection Interfaces)](#topic-5-2)
- [6. 评测与仿真工具 (Benchmarks & Simulators)](#topic-6)
  - [6.1. 评测基准 (Benchmarks)](#topic-6-1)
  - [6.2. 评测指标 (Metrics)](#topic-6-2)
  - [6.3. 物理仿真器 (Physics Simulators)](#topic-6-3)

<a id="topic-1"></a>

## 1. 表征学习 (Representation)

<a id="topic-1-1"></a>

## 1.1. 潜在状态与预测表征 (Latent & Predictive Representations)

### self-supervised learning from images with a joint-embedding predictive architecture (2023)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2301.08243)
- Code: [GitHub](https://github.com/facebookresearch/ijepa)
- Summary: I-JEPA learns semantic image representations by predicting masked target embeddings in latent space.

### v-jepa: latent video prediction for visual representation learning (2024)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2404.08471)
- Code: [官方代码](https://github.com/facebookresearch/jepa)
- Code Notes: 官方训练、评测代码与模型；对应 arXiv:2404.08471。
- Summary: V-JEPA predicts video features in latent space, with representation learning as the primary contribution.

### Perceiver IO: a general architecture for structured inputs and outputs (2022)

- Paper: [论文 / Resource](https://openreview.net/forum?id=fILj7WpI-g)
- Code: [官方代码](https://github.com/google-deepmind/deepmind-research/tree/master/perceiver)
- Code Notes: 官方 JAX/Haiku 实现、推理示例与训练示例。
- Summary: Perceiver IO provides a general latent bottleneck for structured multimodal inputs and outputs.

### V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2603.14482)
- Code: [官方代码](https://github.com/facebookresearch/vjepa2)
- Code Notes: 官方共享仓库，明确包含 V-JEPA 2.1 训练与检查点。
- Summary: V-JEPA 2.1 focuses on dense self-supervised video features and their transfer.

[↑ 返回目录](#目录-contents)


<a id="topic-1-2"></a>

## 1.2. 多模态词元表征 (Multimodal Tokenization)

### world model on million-length video and language with blockwise ringattention (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2402.08268)
- Code: [官方代码](https://github.com/LargeWorldModel/LWM)
- Code Notes: 官方 LWM 训练、推理和模型发布仓库。
- Summary: LWM contributes scalable long-context video-language token processing; generation is a secondary capability.

### video-lavit: unified video-language pre-training with decoupled visual-motional tokenization (2024)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2402.03161)
- Code: [官方代码](https://github.com/jy0205/LaVIT)
- Code Notes: 官方共享仓库；VideoLaVIT 子目录，已确认推理代码和模型。
- Summary: Decoupled visual and motion tokenization is the core representation contribution, supporting multimodal generation.

[↑ 返回目录](#目录-contents)


<a id="topic-1-3"></a>

## 1.3. 结构化世界表征 (Structured Representations)

### 3d gaussian splatting for real-time radiance field rendering (2023)

- Paper: [论文 / Resource](https://doi.org/10.1145/3592433)
- Code: [GitHub](https://github.com/graphdeco-inria/gaussian-splatting)
- Summary: Represents scenes explicitly with 3D Gaussians; rendering/synthesis builds on that structured representation.

### contrastive learning of structured world models (2020)

- Paper: [论文 / Resource](https://arxiv.org/abs/1911.12247)
- Code: [官方代码](https://github.com/tkipf/c-swm)
- Code Notes: 作者明确标注的官方 PyTorch 实现。
- Summary: C-SWM learns object-centric structured states and contrastive transitions.

### Embodied semantic scene graph generation (2021)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v164/li22e.html)
- Code: 待补充（未找到可确认的原论文实现）
- Project / Source: [出版页面](https://proceedings.mlr.press/v164/li22e.html)
- Code Notes: 继续按完整标题和作者核查，仍未发现可靠代码链接。CoRL 2021 会议论文于 PMLR 2022 出版，保留原目录会议年份。
- Summary: Builds an embodied semantic scene graph as an explicit structured world representation.

### Towards spatio-temporal world scene graph generation from monocular videos (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2603.13185)
- Code: [官方代码（部分发布）](https://github.com/rohithpeddi/WorldSGG)
- Code Notes: 作者仓库已提供标注工具与 MLLM 流程；不能视作完整模型和全部数据已发布。
- Summary: Constructs spatio-temporal scene graphs from monocular video.

[↑ 返回目录](#目录-contents)


<a id="topic-2"></a>

## 2. 世界模拟 (Simulation)

<a id="topic-2-1"></a>

## 2.1. 潜在动力学 (Latent Dynamics)

### dream to control: learning behaviors by latent imagination (2020)

- Paper: [论文 / Resource](https://arxiv.org/abs/1912.01603)
- Code: [官方代码](https://github.com/danijar/dreamer)
- Code Notes: Dreamer 第一版官方实现。
- Summary: Dreamer learns a compact latent dynamics model and acts through imagined rollouts.

### mastering atari with discrete world models (2021)

- Paper: [论文 / Resource](https://arxiv.org/abs/2010.02193)
- Code: [官方代码](https://github.com/danijar/dreamerv2)
- Code Notes: DreamerV2 官方实现。
- Summary: Uses a discrete latent world model to simulate trajectories for control.

### Learning interactive world model for object-centric reinforcement learning (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2511.02225)
- Code: 待补充（已找到项目页，未发现代码入口）
- Project: [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm)
- Code Notes: 新增 FIOC-WM 项目页；页面含方法和结果展示，当前未提供公开代码链接。
- Summary: Learns an interactive object-centric dynamics model for reinforcement learning.

### Learning Latent Dynamics for Planning from Pixels (2019)

- Paper: [论文 / Resource](https://openreview.net/forum?id=S1lOTC4tDS)
- Code: [GitHub](https://github.com/danijar/planet)
- Summary: PlaNet learns latent dynamics from pixels and plans through latent rollouts.

### mastering diverse domains through world models (2023)

- Paper: [论文 / Resource](https://arxiv.org/abs/2301.04104)
- Code: [GitHub](https://github.com/danijar/dreamerv3)
- Summary: DreamerV3 centers on scalable latent imagination across diverse control domains.

[↑ 返回目录](#目录-contents)


<a id="topic-2-2"></a>

## 2.2. 视频与交互生成 (Video & Interactive Generation)

### videoworld: exploring knowledge learning from unlabeled videos (2025)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2501.09781)
- Code: [官方代码](https://github.com/ByteDance-Seed/VideoWorld)
- Code Notes: 官方系列仓库；原论文实现位于 VideoWorld 子目录，勿混用 VideoWorld2。
- Summary: Autoregressive video generation and latent dynamics are used to acquire and apply visual knowledge.

### Improving generative imagination in object-centric world models (2020)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v119/lin20f.html)
- Code: [官方代码](https://github.com/zhixuan-lin/G-SWM)
- Code Notes: 官方 PyTorch 实现，含训练、数据生成与预训练模型说明。
- Summary: G-SWM improves object-centric temporal imagination and generative rollout.

### video generation models as world simulators (2024)

- Paper: [论文 / Resource](https://openai.com/index/video-generation-models-as-world-simulators/)
- Code: 待补充（未确认 Sora 原模型官方实现）
- Project / Source: [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/)
- Related Code: [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora)
- Code Notes: Open-Sora 是独立视频生成项目，只作为相关开放研究入口；不代表 OpenAI Sora 源码或原报告复现。
- Summary: Frames large-scale video generation as world simulation; the canonical source is a technical-report webpage.

### genie: generative interactive environments (2024)

- Paper: [论文 / Resource](https://arxiv.org/abs/2402.15391)
- Code: 待补充（官方实现未确认；有社区实现）
- Project: [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/)
- Community Code: [Open-Genie（非官方）](https://github.com/myscience/open-genie)
- Code Notes: Open-Genie 明确声明非官方，提供视频 tokenizer、latent action 和 dynamics 训练入口；尚未验证其训练结果与原论文一致。
- Summary: Generates controllable interactive environments from video data.

### ctrl-world: a controllable generative world model for robot manipulation (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2510.10125)
- Code: [官方代码](https://github.com/Robert-gyj/Ctrl-World)
- Code Notes: 作者的官方 PyTorch 实现，含训练与交互 rollout。
- Summary: Generates controllable robot-manipulation futures, with control as a downstream use.

[↑ 返回目录](#目录-contents)


<a id="topic-2-3"></a>

## 2.3. 三维世界与数据生成 (3D Worlds & Data Generation)

### marble: generative multimodal 3d world model (2025)

- Paper: [论文 / Resource](https://www.worldlabs.ai/)
- Code: 待补充（模型源码未确认；已提供官方 API）
- Project: [Marble 官方文档](https://docs.worldlabs.ai/)
- API: [World API Quickstart](https://docs.worldlabs.ai/api)
- Code Notes: 可通过 World API 调用服务；接口调用示例不等于 Marble 模型源码或可本地运行的权重。
- Summary: A multimodal 3D world-generation system; no archival PDF is specified in the supplied bibliography.

### gigaworld-0: world models as data engine to empower embodied ai (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2511.19861)
- Code: [官方代码](https://github.com/open-gigaai/giga-world-0)
- Code Notes: 官方代码与模型入口；当前说明主要覆盖 Video 分支，不保证全部 3D 流程均发布。
- Summary: Uses a generative world model as a data engine for embodied learning.

[↑ 返回目录](#目录-contents)


<a id="topic-3"></a>

## 3. 行动与控制 (Action)

<a id="topic-3-1"></a>

## 3.1. 策略落地与具身控制 (Policy Grounding & Embodied Control)

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

[↑ 返回目录](#目录-contents)


<a id="topic-3-2"></a>

## 3.2. 视觉语言动作模型 (Vision-Language-Action Models)

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

[↑ 返回目录](#目录-contents)


<a id="topic-3-3"></a>

## 3.3. 世界动作模型 (World Action Models)

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

[↑ 返回目录](#目录-contents)


<a id="topic-4"></a>

## 4. 综述与基础 (Surveys & Foundations)

<a id="topic-4-1"></a>

## 4.1. 综述 (Surveys)

### a survey of embodied world models (2025)

- Paper: 待补充（原目录未提供链接）
- Code: 不适用（综述资料，见 Repository）
- Repository: [综述资料库](https://github.com/tsinghua-fib-lab/Awesome-Embodied-World-Model)
- Code Notes: 同名综述作者维护的论文清单；原条目未给作者/链接，2025 作者上传稿与 2026 仓库引用年份不同，保留年份待核验。
- Summary: Survey of embodied world models; used as background rather than assigned to one model stage.

### a comprehensive survey on world models for embodied ai (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2510.16732)
- Code: 不适用（综述资料，见 Repository）
- Repository: [综述资料库](https://github.com/Li-Zn-H/AwesomeWorldModels)
- Code Notes: 论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。
- Summary: Survey spanning all three stages.

### world model for robot learning: a comprehensive survey (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2605.00080)
- Code: 不适用（综述资料，见 Repository）
- Repository: [综述资料库](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy)
- Code Notes: 论文首页直接链接的官方综述资料库，不是模型实现。
- Summary: Robot-learning world-model survey spanning all three stages.

### the role of world models in shaping autonomous driving: a comprehensive survey (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2502.10498)
- Code: 不适用（综述资料，见 Repository）
- Repository: [综述资料库](https://github.com/LMD0311/Awesome-World-Model)
- Code Notes: 论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。
- Summary: Autonomous-driving world-model survey spanning representation, simulation, and action.

[↑ 返回目录](#目录-contents)


<a id="topic-4-2"></a>

## 4.2. 理论与报告 (Theory & Talks)

### Predictive Learning (2016)

- Paper: [NIPS 2016 官方议程](https://neurips.cc/archive/2016/Schedule.html)
- Code: 不适用（邀请报告，不是独立代码项目）
- Video: [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning)
- Code Notes: 原目录的 “the cake and the cherry” 是概念性条目名，现按可核验的报告名称 Predictive Learning 整理。报告由 Yann LeCun 于 NIPS 2016 发表；录像页面上传于 2017，不能误作报告年份。未核验该比喻在录像中的时间戳。
- Summary: Conceptual presentation motivating predictive learning; it is not an archival model paper.

### the information bottleneck method (2000)

- Paper: [论文 / Resource](https://arxiv.org/abs/physics/0004057)
- Code: 待补充（原作者实现未确认；有社区实现）
- Project / Source: [原论文](https://arxiv.org/abs/physics/0004057)
- Community Code: [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck)
- Code Notes: 社区 Python 实现对应 Tishby 等人的 Information Bottleneck 方法；作者并非原论文署名作者。未确认仓库许可证，不将公开可见等同于已授权开源。论文会议版本为 1999，当前条目保留 arXiv 2000 年份。
- Summary: Information Bottleneck theory underlying task-relevant compression; not itself a world-model architecture.

### Robotics' End Game: Nvidia's Jim Fan (2026)

- Paper: [主办方发布的报告录像](https://www.youtube.com/watch?v=3Y8aq_ofEVs)
- Code: 不适用（会议演讲，不是独立代码项目）
- Video: [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs)
- Code Notes: 已补齐 Sequoia Capital 主办方录像，发布于 2026-04-30。演讲所述模型应分别查阅对应论文条目的代码。
- Summary: Conference presentation rather than an archival paper.

[↑ 返回目录](#目录-contents)


<a id="topic-4-3"></a>

## 4.3. 其他相关系统 (Related Systems)

### DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026)

- Paper: [论文 / Resource](https://doi.org/10.1145/3772318.3790396)
- Code: [官方代码](https://github.com/AkimotoAyako/DroidRetriever)
- Code Notes: 同名系统公开源码，包含跨应用检索核心模块及界面；部分外部依赖需另行安装。
- Summary: Mobile information-retrieval automation is not a core world-model paper; retained because it appears in the supplied bibliography.

[↑ 返回目录](#目录-contents)


<a id="topic-5"></a>

## 5. 数据集与采集工具 (Datasets & Collection)

<a id="topic-5-1"></a>

## 5.1. 数据集 (Datasets)

### Ego4D: around the world in 3,600 hours of egocentric video (2025)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2110.07058)
- Code: [官方工具 / 基线](https://github.com/facebookresearch/Ego4d)
- Code Notes: 官方数据下载、可视化和特征提取工具；数据访问另受数据许可约束。
- Summary: Ego4D is an egocentric video dataset and benchmark suite.

### The Something Something video database for learning and evaluating visual common sense (2017)

- Paper: [论文 / Resource](https://arxiv.org/pdf/1706.04261)
- Code: 不适用（数据集条目，见 Data）
- Data: [官方数据入口（v2）](https://www.qualcomm.com/developer/software/something-something-v-2-dataset)
- Code Notes: 官方数据入口（现提供 v2），不是 2017 v1 的论文模型实现。
- Summary: Something-Something is a human-object action video dataset.

### Scaling egocentric vision: the EPIC-KITCHENS dataset (2018)

- Paper: [论文 / Resource](https://arxiv.org/abs/1804.02748)
- Code: [官方工具 / 基线](https://github.com/epic-kitchens/epic-kitchens-download-scripts)
- Code Notes: 官方数据下载脚本，需区分 EPIC-KITCHENS-55 与后续 100 版本。
- Summary: EPIC-KITCHENS is an egocentric interaction dataset.

### ImageNet Large Scale Visual Recognition Challenge (2015)

- Paper: [论文 / Resource](https://arxiv.org/pdf/1409.0575)
- Code: [官方工具 / 基线](https://image-net.org/challenges/LSVRC/2012/2012-downloads.php)
- Code Notes: 官方 ILSVRC2012 devkit，含 MATLAB 评测例程，非 GitHub 模型仓库。
- Summary: ImageNet/ILSVRC is a visual recognition dataset and benchmark used for representation learning.

### The Kinetics Human Action Video Dataset (2017)

- Paper: [论文 / Resource](https://arxiv.org/pdf/1705.06950)
- Code: [官方工具 / 基线](https://github.com/google-deepmind/kinetics-i3d)
- Code Notes: 原作者团队发布的 Kinetics/I3D 基线模型与推理代码；不是数据本体。
- Summary: Kinetics is a large-scale human-action video dataset.

### Open X-Embodiment: robotic learning datasets and RT-X models (2023)

- Paper: [论文 / Resource](https://arxiv.org/abs/2310.08864)
- Code: [官方工具 / 基线](https://github.com/google-deepmind/open_x_embodiment)
- Code Notes: 官方数据加载示例与 RT-1-X 推理资源；不代表 RT-2-X 完整源码公开。
- Summary: Open X-Embodiment is a robot dataset and RT-X training resource.

[↑ 返回目录](#目录-contents)


<a id="topic-5-2"></a>

## 5.2. 数据采集接口 (Data Collection Interfaces)

### DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2505.21864)
- Code: [官方代码](https://github.com/real-stanford/DexUMI)
- Code Notes: 官方采集系统与部署代码。
- Summary: DexUMI is primarily a manipulation data-collection/interface contribution.

### OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024)

- Paper: [论文 / Resource](https://proceedings.mlr.press/v270/iyer25a.html)
- Code: [官方代码](https://github.com/aadhithya14/Open-Teach)
- Code Notes: 官方 VR、遥操作与示范采集实现。
- Summary: OPEN TEACH is a teleoperation system for collecting manipulation demonstrations.

[↑ 返回目录](#目录-contents)


<a id="topic-6"></a>

## 6. 评测与仿真工具 (Benchmarks & Simulators)

<a id="topic-6-1"></a>

## 6.1. 评测基准 (Benchmarks)

### WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026)

- Paper: [论文 / Resource](https://arxiv.org/abs/2602.08971)
- Code: [官方代码](https://github.com/tsinghua-fib-lab/WorldArena)
- Code Notes: 作者团队维护的官方评测仓库。
- Summary: WorldArena evaluates perception and functional utility rather than proposing one taxonomy-stage model.

### WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026)

- Paper: [论文 / Resource](https://arxiv.org/pdf/2605.17912)
- Code: [官方代码](https://github.com/WorldArena2/WorldArena-2.0)
- Code Notes: 对应 2.0 的独立官方评测仓库。
- Summary: WorldArena 2.0 is an evaluation benchmark spanning modalities, functionality, and platforms.

### CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022)

- Paper: [论文 / Resource](https://doi.org/10.1109/LRA.2022.3180108)
- Code: [官方代码](https://github.com/mees/calvin)
- Code Notes: 官方基准环境、训练和评测实现。
- Summary: CALVIN evaluates long-horizon language-conditioned robot manipulation.

### LIBERO: benchmarking knowledge transfer for lifelong robot learning (2023)

- Paper: [论文 / Resource](https://papers.nips.cc/paper_files/paper/2023/hash/8c3c666820ea055a77726d66fc7d447f-Abstract-Datasets_and_Benchmarks.html)
- Code: [GitHub](https://github.com/Lifelong-Robot-Learning/LIBERO)
- Summary: LIBERO evaluates lifelong robot learning and knowledge transfer.

### LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025)

- Paper: [论文 / Resource](https://arxiv.org/abs/2510.13626)
- Code: [官方代码](https://github.com/sylvestf/LIBERO-plus)
- Code Notes: 对应原论文的官方鲁棒性基准。
- Summary: LIBERO-Plus evaluates VLA robustness and generalization.

[↑ 返回目录](#目录-contents)


<a id="topic-6-2"></a>

## 6.2. 评测指标 (Metrics)

### GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017)

- Paper: [论文 / Resource](https://proceedings.neurips.cc/paper/2017/hash/8a1d694707eb0fefe65871369074926d-Abstract.html)
- Code: [官方代码](https://github.com/bioinf-jku/TTUR)
- Code Notes: 原作者 TTUR/FID 实现。
- Summary: Introduces FID, an evaluation metric for generated-image distributions.

### Towards accurate generative models of video: a new metric and challenges (2018)

- Paper: [论文 / Resource](https://arxiv.org/abs/1812.01717)
- Code: [官方代码](https://github.com/google-research/google-research/tree/master/frechet_video_distance)
- Code Notes: 官方 TensorFlow FVD 实现，README 引用同一论文编号。
- Summary: Introduces and studies FVD for video generation evaluation.

[↑ 返回目录](#目录-contents)


<a id="topic-6-3"></a>

## 6.3. 物理仿真器 (Physics Simulators)

### MuJoCo: a physics engine for model-based control (2012)

- Paper: [论文 / Resource](https://doi.org/10.1109/IROS.2012.6386109)
- Code: [GitHub](https://github.com/google-deepmind/mujoco)
- Summary: MuJoCo is a physics engine used to generate and evaluate interactive trajectories.

[↑ 返回目录](#目录-contents)
