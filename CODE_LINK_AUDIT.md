# 代码与项目备注

[返回论文列表](README.md)

代码链接核查日期：2026-09-12。

### V-JEPA: latent video prediction for visual representation learning (2024)

- 备注：官方训练、评测代码与模型；对应 arXiv:2404.08471。

### Perceiver IO: a general architecture for structured inputs and outputs (2022)

- 备注：官方 JAX/Haiku 实现、推理示例与训练示例。

### V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026)

- 备注：官方共享仓库，明确包含 V-JEPA 2.1 训练与检查点。

### World model on million-length video and language with blockwise ringattention (2025)

- 备注：官方 LWM 训练、推理和模型发布仓库。

### Video-LaVIT: unified video-language pre-training with decoupled visual-motional tokenization (2024)

- 备注：官方共享仓库；VideoLaVIT 子目录，已确认推理代码和模型。

### Contrastive learning of structured world models (2020)

- 备注：官方 PyTorch 实现。

### Embodied semantic scene graph generation (2021)

- Project / Source: [出版页面](https://proceedings.mlr.press/v164/li22e.html)
- 备注：按标题和作者检索，未发现可靠代码链接。CoRL 2021 会议论文于 PMLR 2022 出版，保留原目录会议年份。

### Towards spatio-temporal world scene graph generation from monocular videos (2026)

- 备注：作者仓库已提供标注工具与 MLLM 流程；不能视作完整模型和全部数据已发布。

### Dream to control: learning behaviors by latent imagination (2020)

- 备注：Dreamer 第一版官方实现。

### Mastering atari with discrete world models (2021)

- 备注：DreamerV2 官方实现。

### Learning interactive world model for object-centric reinforcement learning (2025)

- Project: [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm)
- 备注：页面含方法和结果展示，当前未提供公开代码链接。

### VideoWorld: exploring knowledge learning from unlabeled videos (2025)

- 备注：官方系列仓库；原论文实现位于 VideoWorld 子目录，勿混用 VideoWorld2。

### Improving generative imagination in object-centric world models (2020)

- 备注：官方 PyTorch 实现，含训练、数据生成与预训练模型说明。

### Video generation models as world simulators (2024)

- Project / Source: [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/)
- Related Code: [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora)
- 备注：Open-Sora 是独立视频生成项目，只作为相关开放研究入口；不代表 OpenAI Sora 源码或原报告复现。

### Genie: generative interactive environments (2024)

- Project: [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/)
- Community Code: [Open-Genie（非官方）](https://github.com/myscience/open-genie)
- 备注：Open-Genie 明确声明非官方，提供视频 tokenizer、latent action 和 dynamics 训练入口；尚未验证其训练结果与原论文一致。

### Ctrl-World: a controllable generative world model for robot manipulation (2025)

- 备注：作者的官方 PyTorch 实现，含训练与交互 rollout。

### Marble: generative multimodal 3d world model (2025)

- Project: [Marble 官方文档](https://docs.worldlabs.ai/)
- API: [World API Quickstart](https://docs.worldlabs.ai/api)
- 备注：可通过 World API 调用服务；接口调用示例不等于 Marble 模型源码或可本地运行的权重。

### GigaWorld-0: world models as data engine to empower embodied ai (2025)

- 备注：官方代码与模型入口；当前说明主要覆盖 Video 分支，不保证全部 3D 流程均发布。

### Improving vision-and-language navigation with image-text pairs from the web (2020)

- 备注：原论文作者的 VLN-BERT 训练和评测代码。

### Do as I can, not as I say: grounding language in robotic affordances (2022)

- 备注：官方桌面仿真 notebook；不是论文完整真实机器人系统。

### RT-1: robotics transformer for real-world control at scale (2023)

- 备注：官方 RT-1 模型组件、测试与检查点。

### A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026)

- 备注：作者 NeuroVLA 仓库，标题和作者与论文对应。

### PaLM-E: an embodied multimodal language model (2023)

- Project: [官方项目页](https://palm-e.github.io/)
- Community Code: [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E)
- 备注：社区仓库 README 明确说明仅有架构、无预训练权重和 tokenizer。不能据此声称可直接运行原版 PaLM-E 或复现论文结果。

### RT-2: vision-language-action models transfer web knowledge to robotic control (2023)

- Project: [官方项目页](https://robotics-transformer2.github.io/)
- Community Code: [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2)
- 备注：社区仓库作者声明为个人实现，不能视为 Google 原版 RT-2；未验证论文结果、动作解码及真实机器人执行能力。

### Unified vision-language-action model (2025)

- 备注：引用编号为 2506.19850，避免与其他同名 UniVLA 仓库混淆。

### π₀: a vision-language-action flow model for general robot control (2024)

- 备注：官方 openpi，共享训练、微调与推理仓库。

### π₀.₅: a vision-language-action model with open-world generalization (2025)

- 备注：官方 openpi；README 明确支持 π0.5，目前支持 flow-matching head。

### GR00T N1: an open foundation model for generalist humanoid robots (2025)

- 备注：官方 GR00T 系列仓库；主分支已迭代，复现 N1 应使用对应历史版本与权重。

### Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025)

- 备注：OpenVLA-OFT 官方训练、微调与评测实现。

### EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)

- Project: [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/)
- 备注：官方页面仍标注 GitHub (Coming Soon!)。EgoScale 是从人类视频向机器人迁移的 VLA 学习方法，已从数据集分类移到行动 / VLA；后续 GR00T 使用相关数据不等于原论文完整实现已发布。

### DreamDojo: a generalist robot world model from large-scale human videos (2026)

- 备注：官方预训练、后训练、蒸馏和评测代码。

### Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025)

- 备注：作者发布的 RoboTwin 2.0 策略实现；仓库明确不包含模型检查点和数据。

### World action models are zero-shot policies (2026)

- 备注：DreamZero 官方项目页直接链接的预训练、微调与评测仓库。

### MotuBrain: an advanced world action model for robot control (2026)

- Repository: [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain)
- Related Code: [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM)
- 备注：核查仍只见报告、展示材料和许可文件。minWM 是同机构公开的世界模型教程框架，与 MotuBrain 是不同项目。

### A survey of embodied world models (2025)

- Repository: [综述资料库](https://github.com/tsinghua-fib-lab/Awesome-Embodied-World-Model)
- 备注：同名综述作者维护的论文清单；原条目未给作者/链接，2025 作者上传稿与 2026 仓库引用年份不同，保留年份待核验。

### A comprehensive survey on world models for embodied ai (2025)

- Repository: [综述资料库](https://github.com/Li-Zn-H/AwesomeWorldModels)
- 备注：论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。

### World model for robot learning: a comprehensive survey (2026)

- Repository: [综述资料库](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy)
- 备注：论文首页直接链接的官方综述资料库，不是模型实现。

### The role of world models in shaping autonomous driving: a comprehensive survey (2025)

- Repository: [综述资料库](https://github.com/LMD0311/Awesome-World-Model)
- 备注：论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。

### Predictive Learning (2016)

- Video: [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning)
- 备注：原目录的 “the cake and the cherry” 是概念性条目名，现按可核验的报告名称 Predictive Learning 整理。报告由 Yann LeCun 于 NIPS 2016 发表；录像页面上传于 2017，不能误作报告年份。未核验该比喻在录像中的时间戳。

### The information bottleneck method (2000)

- Project / Source: [原论文](https://arxiv.org/abs/physics/0004057)
- Community Code: [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck)
- 备注：社区 Python 实现对应 Tishby 等人的 Information Bottleneck 方法；作者并非原论文署名作者。未确认仓库许可证，不将公开可见等同于已授权开源。论文会议版本为 1999，当前条目保留 arXiv 2000 年份。

### Robotics' End Game: Nvidia's Jim Fan (2026)

- Video: [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs)
- 备注：已补齐 Sequoia Capital 主办方录像，发布于 2026-04-30。演讲所述模型应分别查阅对应论文条目的代码。

### DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026)

- 备注：同名系统公开源码，包含跨应用检索核心模块及界面；部分外部依赖需另行安装。

### Ego4D: around the world in 3,600 hours of egocentric video (2025)

- 备注：官方数据下载、可视化和特征提取工具；数据访问另受数据许可约束。

### The Something Something video database for learning and evaluating visual common sense (2017)

- Data: [官方数据入口（v2）](https://www.qualcomm.com/developer/software/something-something-v-2-dataset)
- 备注：官方数据入口（现提供 v2），不是 2017 v1 的论文模型实现。

### Scaling egocentric vision: the EPIC-KITCHENS dataset (2018)

- 备注：官方数据下载脚本，需区分 EPIC-KITCHENS-55 与后续 100 版本。

### ImageNet Large Scale Visual Recognition Challenge (2015)

- 备注：官方 ILSVRC2012 devkit，含 MATLAB 评测例程，非 GitHub 模型仓库。

### The Kinetics Human Action Video Dataset (2017)

- 备注：原作者团队发布的 Kinetics/I3D 基线模型与推理代码；不是数据本体。

### Open X-Embodiment: robotic learning datasets and RT-X models (2023)

- 备注：官方数据加载示例与 RT-1-X 推理资源；不代表 RT-2-X 完整源码公开。

### DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025)

- 备注：官方采集系统与部署代码。

### OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024)

- 备注：官方 VR、遥操作与示范采集实现。

### WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026)

- 备注：作者团队维护的官方评测仓库。

### WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026)

- 备注：对应 2.0 的独立官方评测仓库。

### CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022)

- 备注：官方基准环境、训练和评测实现。

### LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025)

- 备注：对应原论文的官方鲁棒性基准。

### GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017)

- 备注：原作者 TTUR/FID 实现。

### Towards accurate generative models of video: a new metric and challenges (2018)

- 备注：官方 TensorFlow FVD 实现，README 引用同一论文编号。
