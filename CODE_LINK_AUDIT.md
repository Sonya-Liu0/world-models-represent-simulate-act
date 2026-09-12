# 代码与资源链接核查清单

核查日期：2026-09-12。范围为最初 Code 标为“待补充”的 56 条资源；原已有 8 条代码链接不计入新增。

## 当前结果

- 已补 34 条官方实现链接，其中 3 条注明部分发布；另有 5 条官方工具/基线。
- 已补 4 条综述资料库和 1 条数据入口，它们不作为模型源码统计。
- 剩余 12 条已细分：2 条演讲标为代码不适用；10 条原论文官方实现未确认或待发布。其中 4 条另列社区实现，2 条另列相关独立项目；这些数量有交叉，不能与主统计相加。
- 本轮没有新增可确认的原论文官方模型实现；新增的是社区、项目、API 和演讲入口。所有 64 条资源均保留。

链接经过标题、论文编号、作者或仓库说明核查；未运行训练、推理，也未宣称复现原论文结果。搜索未找到不能证明不存在。社区代码和相关项目独立标注，不能替代官方实现。

[查看本轮 12 条的详细完善结果](RESOURCE_STATUS.md)

## 原始 56 条缺失项与当前结果

| 编号 | 原目录标题 | 当前结果 | 核查入口 |
|---|---|---|---|
| 1 | v-jepa: latent video prediction for visual representation learning (2024) | 官方实现 | [核查入口](https://github.com/facebookresearch/jepa) |
| 2 | Perceiver IO: a general architecture for structured inputs and outputs (2022) | 官方实现 | [核查入口](https://github.com/google-deepmind/deepmind-research/tree/master/perceiver) |
| 3 | V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026) | 官方实现 | [核查入口](https://github.com/facebookresearch/vjepa2) |
| 4 | world model on million-length video and language with blockwise ringattention (2025) | 官方实现 | [核查入口](https://github.com/LargeWorldModel/LWM) |
| 5 | video-lavit: unified video-language pre-training with decoupled visual-motional tokenization (2024) | 官方实现 | [核查入口](https://github.com/jy0205/LaVIT) |
| 6 | contrastive learning of structured world models (2020) | 官方实现 | [核查入口](https://github.com/tkipf/c-swm) |
| 7 | Embodied semantic scene graph generation (2021) | 待补充（未找到可确认的原论文实现） | [出版页面](https://proceedings.mlr.press/v164/li22e.html) |
| 8 | Towards spatio-temporal world scene graph generation from monocular videos (2026) | 官方实现（部分发布） | [核查入口](https://github.com/rohithpeddi/WorldSGG) |
| 9 | dream to control: learning behaviors by latent imagination (2020) | 官方实现 | [核查入口](https://github.com/danijar/dreamer) |
| 10 | mastering atari with discrete world models (2021) | 官方实现 | [核查入口](https://github.com/danijar/dreamerv2) |
| 11 | Learning interactive world model for object-centric reinforcement learning (2025) | 待补充（已找到项目页，未发现代码入口） | [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm) |
| 12 | videoworld: exploring knowledge learning from unlabeled videos (2025) | 官方实现 | [核查入口](https://github.com/ByteDance-Seed/VideoWorld) |
| 13 | Improving generative imagination in object-centric world models (2020) | 官方实现 | [核查入口](https://github.com/zhixuan-lin/G-SWM) |
| 14 | video generation models as world simulators (2024) | 待补充（未确认 Sora 原模型官方实现） | [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/) · [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora) |
| 15 | genie: generative interactive environments (2024) | 待补充（官方实现未确认；有社区实现） | [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/) · [Open-Genie（非官方）](https://github.com/myscience/open-genie) |
| 16 | ctrl-world: a controllable generative world model for robot manipulation (2025) | 官方实现 | [核查入口](https://github.com/Robert-gyj/Ctrl-World) |
| 17 | marble: generative multimodal 3d world model (2025) | 待补充（模型源码未确认；已提供官方 API） | [Marble 官方文档](https://docs.worldlabs.ai/) · [World API Quickstart](https://docs.worldlabs.ai/api) |
| 18 | gigaworld-0: world models as data engine to empower embodied ai (2025) | 官方实现 | [核查入口](https://github.com/open-gigaai/giga-world-0) |
| 19 | Improving vision-and-language navigation with image-text pairs from the web (2020) | 官方实现 | [核查入口](https://github.com/arjunmajum/vln-bert) |
| 20 | Do as I can, not as I say: grounding language in robotic affordances (2022) | 官方实现（部分发布） | [核查入口](https://github.com/google-research/google-research/tree/master/saycan) |
| 21 | RT-1: robotics transformer for real-world control at scale (2023) | 官方实现 | [核查入口](https://github.com/google-research/robotics_transformer) |
| 22 | A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026) | 官方实现 | [核查入口](https://github.com/guoweiyu/NeuroVLA) |
| 23 | PaLM-E: an embodied multimodal language model (2023) | 待补充（官方实现未确认；有社区架构实现） | [官方项目页](https://palm-e.github.io/) · [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E) |
| 24 | rt-2: vision-language-action models transfer web knowledge to robotic control (2023) | 待补充（官方实现未确认；有社区实现） | [官方项目页](https://robotics-transformer2.github.io/) · [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2) |
| 25 | unified vision-language-action model (2025) | 官方实现 | [核查入口](https://github.com/baaivision/UniVLA) |
| 26 | $pi_0$: a vision-language-action flow model for general robot control (2024) | 官方实现 | [核查入口](https://github.com/Physical-Intelligence/openpi) |
| 27 | $pi_0.5$: a vision-language-action model with open-world generalization (2025) | 官方实现 | [核查入口](https://github.com/Physical-Intelligence/openpi) |
| 28 | GR00T N1: an open foundation model for generalist humanoid robots (2025) | 官方实现 | [核查入口](https://github.com/NVIDIA/Isaac-GR00T) |
| 29 | Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025) | 官方实现 | [核查入口](https://github.com/moojink/openvla-oft) |
| 30 | DreamDojo: a generalist robot world model from large-scale human videos (2026) | 官方实现 | [核查入口](https://github.com/NVIDIA/DreamDojo) |
| 31 | Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025) | 官方实现（部分发布） | [核查入口](https://github.com/jiayueru/Video2Act) |
| 32 | World action models are zero-shot policies (2026) | 官方实现 | [核查入口](https://github.com/dreamzero0/dreamzero) |
| 33 | MotuBrain: an advanced world action model for robot control (2026) | 待补充（官方仓库已建，未发现模型源码） | [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain) · [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM) |
| 34 | a survey of embodied world models (2025) | 综述资料库 | [核查入口](https://github.com/tsinghua-fib-lab/Awesome-Embodied-World-Model) |
| 35 | a comprehensive survey on world models for embodied ai (2025) | 综述资料库 | [核查入口](https://github.com/Li-Zn-H/AwesomeWorldModels) |
| 36 | world model for robot learning: a comprehensive survey (2026) | 综述资料库 | [核查入口](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy) |
| 37 | the role of world models in shaping autonomous driving: a comprehensive survey (2025) | 综述资料库 | [核查入口](https://github.com/LMD0311/Awesome-World-Model) |
| 38 | the cake and the cherry (2016) | 不适用（邀请报告，不是独立代码项目） | [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning) |
| 39 | the information bottleneck method (2000) | 待补充（原作者实现未确认；有社区实现） | [原论文](https://arxiv.org/abs/physics/0004057) · [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck) |
| 40 | Robotics' end game (2026) | 不适用（会议演讲，不是独立代码项目） | [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs) |
| 41 | DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026) | 官方实现 | [核查入口](https://github.com/AkimotoAyako/DroidRetriever) |
| 42 | Ego4D: around the world in 3,600 hours of egocentric video (2025) | 官方工具 / 基线 | [核查入口](https://github.com/facebookresearch/Ego4d) |
| 43 | EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026) | 待发布（官方页面标注 Coming Soon） | [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/) |
| 44 | The Something Something video database for learning and evaluating visual common sense (2017) | 数据入口 | [核查入口](https://www.qualcomm.com/developer/software/something-something-v-2-dataset) |
| 45 | Scaling egocentric vision: the EPIC-KITCHENS dataset (2018) | 官方工具 / 基线 | [核查入口](https://github.com/epic-kitchens/epic-kitchens-download-scripts) |
| 46 | ImageNet Large Scale Visual Recognition Challenge (2015) | 官方工具 / 基线 | [核查入口](https://image-net.org/challenges/LSVRC/2012/2012-downloads.php) |
| 47 | The Kinetics Human Action Video Dataset (2017) | 官方工具 / 基线 | [核查入口](https://github.com/google-deepmind/kinetics-i3d) |
| 48 | Open X-Embodiment: robotic learning datasets and RT-X models (2023) | 官方工具 / 基线 | [核查入口](https://github.com/google-deepmind/open_x_embodiment) |
| 49 | DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025) | 官方实现 | [核查入口](https://github.com/real-stanford/DexUMI) |
| 50 | OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024) | 官方实现 | [核查入口](https://github.com/aadhithya14/Open-Teach) |
| 51 | WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026) | 官方实现 | [核查入口](https://github.com/tsinghua-fib-lab/WorldArena) |
| 52 | WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026) | 官方实现 | [核查入口](https://github.com/WorldArena2/WorldArena-2.0) |
| 53 | CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022) | 官方实现 | [核查入口](https://github.com/mees/calvin) |
| 54 | LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025) | 官方实现 | [核查入口](https://github.com/sylvestf/LIBERO-plus) |
| 55 | GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017) | 官方实现 | [核查入口](https://github.com/bioinf-jku/TTUR) |
| 56 | Towards accurate generative models of video: a new metric and challenges (2018) | 官方实现 | [核查入口](https://github.com/google-research/google-research/tree/master/frechet_video_distance) |

## 逐项说明

### 1. v-jepa: latent video prediction for visual representation learning (2024)

- 原目录标题: v-jepa: latent video prediction for visual representation learning (2024)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2404.08471)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/facebookresearch/jepa)
- 核查说明: 官方训练、评测代码与模型；对应 arXiv:2404.08471。

### 2. Perceiver IO: a general architecture for structured inputs and outputs (2022)

- 原目录标题: Perceiver IO: a general architecture for structured inputs and outputs (2022)
- 原 Paper: [论文 / Resource](https://openreview.net/forum?id=fILj7WpI-g)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/google-deepmind/deepmind-research/tree/master/perceiver)
- 核查说明: 官方 JAX/Haiku 实现、推理示例与训练示例。

### 3. V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026)

- 原目录标题: V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2603.14482)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/facebookresearch/vjepa2)
- 核查说明: 官方共享仓库，明确包含 V-JEPA 2.1 训练与检查点。

### 4. world model on million-length video and language with blockwise ringattention (2025)

- 原目录标题: world model on million-length video and language with blockwise ringattention (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2402.08268)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/LargeWorldModel/LWM)
- 核查说明: 官方 LWM 训练、推理和模型发布仓库。

### 5. video-lavit: unified video-language pre-training with decoupled visual-motional tokenization (2024)

- 原目录标题: video-lavit: unified video-language pre-training with decoupled visual-motional tokenization (2024)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2402.03161)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/jy0205/LaVIT)
- 核查说明: 官方共享仓库；VideoLaVIT 子目录，已确认推理代码和模型。

### 6. contrastive learning of structured world models (2020)

- 原目录标题: contrastive learning of structured world models (2020)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/1911.12247)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/tkipf/c-swm)
- 核查说明: 作者明确标注的官方 PyTorch 实现。

### 7. Embodied semantic scene graph generation (2021)

- 原目录标题: Embodied semantic scene graph generation (2021)
- 原 Paper: [论文 / Resource](https://proceedings.mlr.press/v164/li22e.html)
- 原 Code: 待补充
- 当前状态: 待补充（未找到可确认的原论文实现）
- Project / Source: [出版页面](https://proceedings.mlr.press/v164/li22e.html)
- 核查说明: 继续按完整标题和作者核查，仍未发现可靠代码链接。CoRL 2021 会议论文于 PMLR 2022 出版，保留原目录会议年份。

### 8. Towards spatio-temporal world scene graph generation from monocular videos (2026)

- 原目录标题: Towards spatio-temporal world scene graph generation from monocular videos (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2603.13185)
- 原 Code: 待补充
- 当前状态: 官方实现（部分发布）
- Source: [核查入口](https://github.com/rohithpeddi/WorldSGG)
- 核查说明: 作者仓库已提供标注工具与 MLLM 流程；不能视作完整模型和全部数据已发布。

### 9. dream to control: learning behaviors by latent imagination (2020)

- 原目录标题: dream to control: learning behaviors by latent imagination (2020)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/1912.01603)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/danijar/dreamer)
- 核查说明: Dreamer 第一版官方实现。

### 10. mastering atari with discrete world models (2021)

- 原目录标题: mastering atari with discrete world models (2021)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2010.02193)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/danijar/dreamerv2)
- 核查说明: DreamerV2 官方实现。

### 11. Learning interactive world model for object-centric reinforcement learning (2025)

- 原目录标题: Learning interactive world model for object-centric reinforcement learning (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2511.02225)
- 原 Code: 待补充
- 当前状态: 待补充（已找到项目页，未发现代码入口）
- Project: [FIOC-WM 项目页](https://sites.google.com/view/fioc-wm)
- 核查说明: 新增 FIOC-WM 项目页；页面含方法和结果展示，当前未提供公开代码链接。

### 12. videoworld: exploring knowledge learning from unlabeled videos (2025)

- 原目录标题: videoworld: exploring knowledge learning from unlabeled videos (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2501.09781)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/ByteDance-Seed/VideoWorld)
- 核查说明: 官方系列仓库；原论文实现位于 VideoWorld 子目录，勿混用 VideoWorld2。

### 13. Improving generative imagination in object-centric world models (2020)

- 原目录标题: Improving generative imagination in object-centric world models (2020)
- 原 Paper: [论文 / Resource](https://proceedings.mlr.press/v119/lin20f.html)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/zhixuan-lin/G-SWM)
- 核查说明: 官方 PyTorch 实现，含训练、数据生成与预训练模型说明。

### 14. video generation models as world simulators (2024)

- 原目录标题: video generation models as world simulators (2024)
- 原 Paper: [论文 / Resource](https://openai.com/index/video-generation-models-as-world-simulators/)
- 原 Code: 待补充
- 当前状态: 待补充（未确认 Sora 原模型官方实现）
- Project / Source: [官方技术报告](https://openai.com/index/video-generation-models-as-world-simulators/)
- Related Code: [Open-Sora（独立项目）](https://github.com/hpcaitech/Open-Sora)
- 核查说明: Open-Sora 是独立视频生成项目，只作为相关开放研究入口；不代表 OpenAI Sora 源码或原报告复现。

### 15. genie: generative interactive environments (2024)

- 原目录标题: genie: generative interactive environments (2024)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2402.15391)
- 原 Code: 待补充
- 当前状态: 待补充（官方实现未确认；有社区实现）
- Project: [DeepMind 原论文页面](https://deepmind.google/research/publications/60474/)
- Community Code: [Open-Genie（非官方）](https://github.com/myscience/open-genie)
- 核查说明: Open-Genie 明确声明非官方，提供视频 tokenizer、latent action 和 dynamics 训练入口；尚未验证其训练结果与原论文一致。

### 16. ctrl-world: a controllable generative world model for robot manipulation (2025)

- 原目录标题: ctrl-world: a controllable generative world model for robot manipulation (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2510.10125)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/Robert-gyj/Ctrl-World)
- 核查说明: 作者的官方 PyTorch 实现，含训练与交互 rollout。

### 17. marble: generative multimodal 3d world model (2025)

- 原目录标题: marble: generative multimodal 3d world model (2025)
- 原 Paper: [论文 / Resource](https://www.worldlabs.ai/)
- 原 Code: 待补充
- 当前状态: 待补充（模型源码未确认；已提供官方 API）
- Project: [Marble 官方文档](https://docs.worldlabs.ai/)
- API: [World API Quickstart](https://docs.worldlabs.ai/api)
- 核查说明: 可通过 World API 调用服务；接口调用示例不等于 Marble 模型源码或可本地运行的权重。

### 18. gigaworld-0: world models as data engine to empower embodied ai (2025)

- 原目录标题: gigaworld-0: world models as data engine to empower embodied ai (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2511.19861)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/open-gigaai/giga-world-0)
- 核查说明: 官方代码与模型入口；当前说明主要覆盖 Video 分支，不保证全部 3D 流程均发布。

### 19. Improving vision-and-language navigation with image-text pairs from the web (2020)

- 原目录标题: Improving vision-and-language navigation with image-text pairs from the web (2020)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2004.14973)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/arjunmajum/vln-bert)
- 核查说明: 原论文作者的 VLN-BERT 训练和评测代码。

### 20. Do as I can, not as I say: grounding language in robotic affordances (2022)

- 原目录标题: Do as I can, not as I say: grounding language in robotic affordances (2022)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2204.01691)
- 原 Code: 待补充
- 当前状态: 官方实现（部分发布）
- Source: [核查入口](https://github.com/google-research/google-research/tree/master/saycan)
- 核查说明: 官方桌面仿真 notebook；不是论文完整真实机器人系统。

### 21. RT-1: robotics transformer for real-world control at scale (2023)

- 原目录标题: RT-1: robotics transformer for real-world control at scale (2023)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2212.06817)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/google-research/robotics_transformer)
- 核查说明: 官方 RT-1 模型组件、测试与检查点。

### 22. A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026)

- 原目录标题: A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2601.14628)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/guoweiyu/NeuroVLA)
- 核查说明: 作者 NeuroVLA 仓库，标题和作者与论文对应。

### 23. PaLM-E: an embodied multimodal language model (2023)

- 原目录标题: PaLM-E: an embodied multimodal language model (2023)
- 原 Paper: [论文 / Resource](https://proceedings.mlr.press/v202/driess23a.html)
- 原 Code: 待补充
- 当前状态: 待补充（官方实现未确认；有社区架构实现）
- Project: [官方项目页](https://palm-e.github.io/)
- Community Code: [PALM-E 架构实现（非官方）](https://github.com/kyegomez/PALM-E)
- 核查说明: 社区仓库 README 明确说明仅有架构、无预训练权重和 tokenizer。不能据此声称可直接运行原版 PaLM-E 或复现论文结果。

### 24. rt-2: vision-language-action models transfer web knowledge to robotic control (2023)

- 原目录标题: rt-2: vision-language-action models transfer web knowledge to robotic control (2023)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2307.15818)
- 原 Code: 待补充
- 当前状态: 待补充（官方实现未确认；有社区实现）
- Project: [官方项目页](https://robotics-transformer2.github.io/)
- Community Code: [RT-2 社区实现（非官方）](https://github.com/kyegomez/RT-2)
- 核查说明: 社区仓库作者声明为个人实现，不能视为 Google 原版 RT-2；未验证论文结果、动作解码及真实机器人执行能力。

### 25. unified vision-language-action model (2025)

- 原目录标题: unified vision-language-action model (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2506.19850)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/baaivision/UniVLA)
- 核查说明: 引用编号为 2506.19850，避免与其他同名 UniVLA 仓库混淆。

### 26. $pi_0$: a vision-language-action flow model for general robot control (2024)

- 原目录标题: $pi_0$: a vision-language-action flow model for general robot control (2024)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2410.24164)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/Physical-Intelligence/openpi)
- 核查说明: 官方 openpi，共享训练、微调与推理仓库。

### 27. $pi_0.5$: a vision-language-action model with open-world generalization (2025)

- 原目录标题: $pi_0.5$: a vision-language-action model with open-world generalization (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2504.16054)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/Physical-Intelligence/openpi)
- 核查说明: 官方 openpi；README 明确支持 π0.5，目前支持 flow-matching head。

### 28. GR00T N1: an open foundation model for generalist humanoid robots (2025)

- 原目录标题: GR00T N1: an open foundation model for generalist humanoid robots (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2503.14734)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/NVIDIA/Isaac-GR00T)
- 核查说明: 官方 GR00T 系列仓库；主分支已迭代，复现 N1 应使用对应历史版本与权重。

### 29. Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025)

- 原目录标题: Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2502.19645)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/moojink/openvla-oft)
- 核查说明: OpenVLA-OFT 官方训练、微调与评测实现。

### 30. DreamDojo: a generalist robot world model from large-scale human videos (2026)

- 原目录标题: DreamDojo: a generalist robot world model from large-scale human videos (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2602.06949)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/NVIDIA/DreamDojo)
- 核查说明: 官方预训练、后训练、蒸馏和评测代码。

### 31. Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025)

- 原目录标题: Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2512.03044)
- 原 Code: 待补充
- 当前状态: 官方实现（部分发布）
- Source: [核查入口](https://github.com/jiayueru/Video2Act)
- 核查说明: 作者发布的 RoboTwin 2.0 策略实现；仓库明确不包含模型检查点和数据。

### 32. World action models are zero-shot policies (2026)

- 原目录标题: World action models are zero-shot policies (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2602.15922)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/dreamzero0/dreamzero)
- 核查说明: DreamZero 官方项目页直接链接的预训练、微调与评测仓库。

### 33. MotuBrain: an advanced world action model for robot control (2026)

- 原目录标题: MotuBrain: an advanced world action model for robot control (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2604.27792)
- 原 Code: 待补充
- 当前状态: 待补充（官方仓库已建，未发现模型源码）
- Repository: [MotuBrain 官方仓库](https://github.com/shengshu-ai/Motubrain)
- Related Code: [minWM（同机构的独立框架）](https://github.com/shengshu-ai/minWM)
- 核查说明: 本轮复查仍只见报告、展示材料和许可文件。minWM 是同机构公开的世界模型教程框架，与 MotuBrain 是不同项目。

### 34. a survey of embodied world models (2025)

- 原目录标题: a survey of embodied world models (2025)
- 原 Paper: 待补充（原目录未提供链接）
- 原 Code: 待补充
- 当前状态: 综述资料库
- Source: [核查入口](https://github.com/tsinghua-fib-lab/Awesome-Embodied-World-Model)
- 核查说明: 同名综述作者维护的论文清单；原条目未给作者/链接，2025 作者上传稿与 2026 仓库引用年份不同，保留年份待核验。

### 35. a comprehensive survey on world models for embodied ai (2025)

- 原目录标题: a comprehensive survey on world models for embodied ai (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2510.16732)
- 原 Code: 待补充
- 当前状态: 综述资料库
- Source: [核查入口](https://github.com/Li-Zn-H/AwesomeWorldModels)
- 核查说明: 论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。

### 36. world model for robot learning: a comprehensive survey (2026)

- 原目录标题: world model for robot learning: a comprehensive survey (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2605.00080)
- 原 Code: 待补充
- 当前状态: 综述资料库
- Source: [核查入口](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy)
- 核查说明: 论文首页直接链接的官方综述资料库，不是模型实现。

### 37. the role of world models in shaping autonomous driving: a comprehensive survey (2025)

- 原目录标题: the role of world models in shaping autonomous driving: a comprehensive survey (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2502.10498)
- 原 Code: 待补充
- 当前状态: 综述资料库
- Source: [核查入口](https://github.com/LMD0311/Awesome-World-Model)
- 核查说明: 论文 arXiv 页面直接链接的官方综述资料库，不是模型实现。

### 38. Predictive Learning (2016)

- 原目录标题: the cake and the cherry (2016)
- 原 Paper: 待补充（原目录未提供链接）
- 原 Code: 待补充
- 当前状态: 不适用（邀请报告，不是独立代码项目）
- Video: [Predictive Learning 会议录像](https://learn.microsoft.com/en-us/shows/neural-information-processing-systems-conference-nips-2016/predictive-learning)
- 核查说明: 原目录的 “the cake and the cherry” 是概念性条目名，现按可核验的报告名称 Predictive Learning 整理。报告由 Yann LeCun 于 NIPS 2016 发表；录像页面上传于 2017，不能误作报告年份。未核验该比喻在录像中的时间戳。

### 39. the information bottleneck method (2000)

- 原目录标题: the information bottleneck method (2000)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/physics/0004057)
- 原 Code: 待补充
- 当前状态: 待补充（原作者实现未确认；有社区实现）
- Project / Source: [原论文](https://arxiv.org/abs/physics/0004057)
- Community Code: [Information Bottleneck（非官方，许可证未确认）](https://github.com/ravidziv/Information-bottleneck)
- 核查说明: 社区 Python 实现对应 Tishby 等人的 Information Bottleneck 方法；作者并非原论文署名作者。未确认仓库许可证，不将公开可见等同于已授权开源。论文会议版本为 1999，当前条目保留 arXiv 2000 年份。

### 40. Robotics' End Game: Nvidia's Jim Fan (2026)

- 原目录标题: Robotics' end game (2026)
- 原 Paper: 待补充（原目录未提供链接）
- 原 Code: 待补充
- 当前状态: 不适用（会议演讲，不是独立代码项目）
- Video: [Sequoia Capital 官方视频](https://www.youtube.com/watch?v=3Y8aq_ofEVs)
- 核查说明: 已补齐 Sequoia Capital 主办方录像，发布于 2026-04-30。演讲所述模型应分别查阅对应论文条目的代码。

### 41. DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026)

- 原目录标题: DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026)
- 原 Paper: [论文 / Resource](https://doi.org/10.1145/3772318.3790396)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/AkimotoAyako/DroidRetriever)
- 核查说明: 同名系统公开源码，包含跨应用检索核心模块及界面；部分外部依赖需另行安装。

### 42. Ego4D: around the world in 3,600 hours of egocentric video (2025)

- 原目录标题: Ego4D: around the world in 3,600 hours of egocentric video (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2110.07058)
- 原 Code: 待补充
- 当前状态: 官方工具 / 基线
- Source: [核查入口](https://github.com/facebookresearch/Ego4d)
- 核查说明: 官方数据下载、可视化和特征提取工具；数据访问另受数据许可约束。

### 43. EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)

- 原目录标题: EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2602.16710)
- 原 Code: 待补充
- 当前状态: 待发布（官方页面标注 Coming Soon）
- Project: [NVIDIA EgoScale 官方项目页](https://research.nvidia.com/labs/gear/egoscale/)
- 核查说明: 官方页面仍标注 GitHub (Coming Soon!)。EgoScale 是从人类视频向机器人迁移的 VLA 学习方法，已从数据集分类移到行动 / VLA；后续 GR00T 使用相关数据不等于原论文完整实现已发布。

### 44. The Something Something video database for learning and evaluating visual common sense (2017)

- 原目录标题: The Something Something video database for learning and evaluating visual common sense (2017)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/1706.04261)
- 原 Code: 待补充
- 当前状态: 数据入口
- Source: [核查入口](https://www.qualcomm.com/developer/software/something-something-v-2-dataset)
- 核查说明: 官方数据入口（现提供 v2），不是 2017 v1 的论文模型实现。

### 45. Scaling egocentric vision: the EPIC-KITCHENS dataset (2018)

- 原目录标题: Scaling egocentric vision: the EPIC-KITCHENS dataset (2018)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/1804.02748)
- 原 Code: 待补充
- 当前状态: 官方工具 / 基线
- Source: [核查入口](https://github.com/epic-kitchens/epic-kitchens-download-scripts)
- 核查说明: 官方数据下载脚本，需区分 EPIC-KITCHENS-55 与后续 100 版本。

### 46. ImageNet Large Scale Visual Recognition Challenge (2015)

- 原目录标题: ImageNet Large Scale Visual Recognition Challenge (2015)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/1409.0575)
- 原 Code: 待补充
- 当前状态: 官方工具 / 基线
- Source: [核查入口](https://image-net.org/challenges/LSVRC/2012/2012-downloads.php)
- 核查说明: 官方 ILSVRC2012 devkit，含 MATLAB 评测例程，非 GitHub 模型仓库。

### 47. The Kinetics Human Action Video Dataset (2017)

- 原目录标题: The Kinetics Human Action Video Dataset (2017)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/1705.06950)
- 原 Code: 待补充
- 当前状态: 官方工具 / 基线
- Source: [核查入口](https://github.com/google-deepmind/kinetics-i3d)
- 核查说明: 原作者团队发布的 Kinetics/I3D 基线模型与推理代码；不是数据本体。

### 48. Open X-Embodiment: robotic learning datasets and RT-X models (2023)

- 原目录标题: Open X-Embodiment: robotic learning datasets and RT-X models (2023)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2310.08864)
- 原 Code: 待补充
- 当前状态: 官方工具 / 基线
- Source: [核查入口](https://github.com/google-deepmind/open_x_embodiment)
- 核查说明: 官方数据加载示例与 RT-1-X 推理资源；不代表 RT-2-X 完整源码公开。

### 49. DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025)

- 原目录标题: DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2505.21864)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/real-stanford/DexUMI)
- 核查说明: 官方采集系统与部署代码。

### 50. OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024)

- 原目录标题: OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024)
- 原 Paper: [论文 / Resource](https://proceedings.mlr.press/v270/iyer25a.html)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/aadhithya14/Open-Teach)
- 核查说明: 官方 VR、遥操作与示范采集实现。

### 51. WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026)

- 原目录标题: WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2602.08971)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/tsinghua-fib-lab/WorldArena)
- 核查说明: 作者团队维护的官方评测仓库。

### 52. WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026)

- 原目录标题: WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026)
- 原 Paper: [论文 / Resource](https://arxiv.org/pdf/2605.17912)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/WorldArena2/WorldArena-2.0)
- 核查说明: 对应 2.0 的独立官方评测仓库。

### 53. CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022)

- 原目录标题: CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022)
- 原 Paper: [论文 / Resource](https://doi.org/10.1109/LRA.2022.3180108)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/mees/calvin)
- 核查说明: 官方基准环境、训练和评测实现。

### 54. LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025)

- 原目录标题: LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/2510.13626)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/sylvestf/LIBERO-plus)
- 核查说明: 对应原论文的官方鲁棒性基准。

### 55. GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017)

- 原目录标题: GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017)
- 原 Paper: [论文 / Resource](https://proceedings.neurips.cc/paper/2017/hash/8a1d694707eb0fefe65871369074926d-Abstract.html)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/bioinf-jku/TTUR)
- 核查说明: 原作者 TTUR/FID 实现。

### 56. Towards accurate generative models of video: a new metric and challenges (2018)

- 原目录标题: Towards accurate generative models of video: a new metric and challenges (2018)
- 原 Paper: [论文 / Resource](https://arxiv.org/abs/1812.01717)
- 原 Code: 待补充
- 当前状态: 官方实现
- Source: [核查入口](https://github.com/google-research/google-research/tree/master/frechet_video_distance)
- 核查说明: 官方 TensorFlow FVD 实现，README 引用同一论文编号。

[返回完整列表](WORLD_MODELS.md)
