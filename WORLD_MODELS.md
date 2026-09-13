# World Models: Represent, Simulate, and Act

整理世界模型相关论文和代码，包括表征学习、世界模拟、行动与控制，以及综述、数据集和评测工具。

〖Contents〗

- [1.表征学习(Representation)](#topic-1)
- [2.世界模拟(Simulation)](#topic-2)
- [3.行动与控制(Action)](#topic-3)
- [4.综述与基础(Surveys & Foundations)](#topic-4)
- [5.数据集与采集工具(Datasets & Collection)](#topic-5)
- [6.评测与仿真工具(Benchmarks & Simulators)](#topic-6)

<a id="topic-1"></a>

# 1.表征学习(Representation)

### Self-supervised learning from images with a joint-embedding predictive architecture (2023)

- Paper: <https://arxiv.org/pdf/2301.08243>
- Code: <https://github.com/facebookresearch/ijepa>

### V-JEPA: latent video prediction for visual representation learning (2024)

- Paper: <https://arxiv.org/pdf/2404.08471>
- Code: <https://github.com/facebookresearch/jepa>

### Perceiver IO: a general architecture for structured inputs and outputs (2022)

- Paper: <https://openreview.net/forum?id=fILj7WpI-g>
- Code: <https://github.com/google-deepmind/deepmind-research/tree/master/perceiver>

### V-JEPA 2.1: Unlocking Dense Features in Video Self-Supervised Learning (2026)

- Paper: <https://arxiv.org/abs/2603.14482>
- Code: <https://github.com/facebookresearch/vjepa2>

### World model on million-length video and language with blockwise ringattention (2025)

- Paper: <https://arxiv.org/abs/2402.08268>
- Code: <https://github.com/LargeWorldModel/LWM>

### Video-LaVIT: unified video-language pre-training with decoupled visual-motional tokenization (2024)

- Paper: <https://arxiv.org/pdf/2402.03161>
- Code: <https://github.com/jy0205/LaVIT>

### 3D gaussian splatting for real-time radiance field rendering (2023)

- Paper: <https://doi.org/10.1145/3592433>
- Code: <https://github.com/graphdeco-inria/gaussian-splatting>

### Contrastive learning of structured world models (2020)

- Paper: <https://arxiv.org/abs/1911.12247>
- Code: <https://github.com/tkipf/c-swm>

### Embodied semantic scene graph generation (2021)

- Paper: <https://proceedings.mlr.press/v164/li22e.html>
- Code: 待补充

### Towards spatio-temporal world scene graph generation from monocular videos (2026)

- Paper: <https://arxiv.org/abs/2603.13185>
- Code: <https://github.com/rohithpeddi/WorldSGG>（部分发布）

<a id="topic-2"></a>

# 2.世界模拟(Simulation)

### Dream to control: learning behaviors by latent imagination (2020)

- Paper: <https://arxiv.org/abs/1912.01603>
- Code: <https://github.com/danijar/dreamer>

### Mastering atari with discrete world models (2021)

- Paper: <https://arxiv.org/abs/2010.02193>
- Code: <https://github.com/danijar/dreamerv2>

### Learning interactive world model for object-centric reinforcement learning (2025)

- Paper: <https://arxiv.org/abs/2511.02225>
- Code: 待补充

### Learning Latent Dynamics for Planning from Pixels (2019)

- Paper: <https://openreview.net/forum?id=S1lOTC4tDS>
- Code: <https://github.com/danijar/planet>

### Mastering diverse domains through world models (2023)

- Paper: <https://arxiv.org/abs/2301.04104>
- Code: <https://github.com/danijar/dreamerv3>

### VideoWorld: exploring knowledge learning from unlabeled videos (2025)

- Paper: <https://arxiv.org/pdf/2501.09781>
- Code: <https://github.com/ByteDance-Seed/VideoWorld>

### Improving generative imagination in object-centric world models (2020)

- Paper: <https://proceedings.mlr.press/v119/lin20f.html>
- Code: <https://github.com/zhixuan-lin/G-SWM>

### Video generation models as world simulators (2024)

- Paper: <https://openai.com/index/video-generation-models-as-world-simulators/>
- Code: 待补充

### Genie: generative interactive environments (2024)

- Paper: <https://arxiv.org/abs/2402.15391>
- Code: 待补充

### Ctrl-World: a controllable generative world model for robot manipulation (2025)

- Paper: <https://arxiv.org/abs/2510.10125>
- Code: <https://github.com/Robert-gyj/Ctrl-World>

### Marble: generative multimodal 3d world model (2025)

- Paper: <https://www.worldlabs.ai/>
- Code: 待补充

### GigaWorld-0: world models as data engine to empower embodied ai (2025)

- Paper: <https://arxiv.org/abs/2511.19861>
- Code: <https://github.com/open-gigaai/giga-world-0>（Video 分支）

<a id="topic-3"></a>

# 3.行动与控制(Action)

### Improving vision-and-language navigation with image-text pairs from the web (2020)

- Paper: <https://arxiv.org/pdf/2004.14973>
- Code: <https://github.com/arjunmajum/vln-bert>

### CLIPort: what and where pathways for robotic manipulation (2021)

- Paper: <https://proceedings.mlr.press/v164/shridhar22a.html>
- Code: <https://github.com/cliport/cliport>

### Do as I can, not as I say: grounding language in robotic affordances (2022)

- Paper: <https://arxiv.org/pdf/2204.01691>
- Code: <https://github.com/google-research/google-research/tree/master/saycan>（部分发布）

### RT-1: robotics transformer for real-world control at scale (2023)

- Paper: <https://arxiv.org/pdf/2212.06817>
- Code: <https://github.com/google-research/robotics_transformer>

### A brain-inspired embodied intelligence for fluid and fast reflexive robotics control (2026)

- Paper: <https://arxiv.org/abs/2601.14628>
- Code: <https://github.com/guoweiyu/NeuroVLA>

### PaLM-E: an embodied multimodal language model (2023)

- Paper: <https://proceedings.mlr.press/v202/driess23a.html>
- Code: 待补充

### RT-2: vision-language-action models transfer web knowledge to robotic control (2023)

- Paper: <https://arxiv.org/abs/2307.15818>
- Code: 待补充

### Unified vision-language-action model (2025)

- Paper: <https://arxiv.org/abs/2506.19850>
- Code: <https://github.com/baaivision/UniVLA>

### OpenVLA: an open-source vision-language-action model (2024)

- Paper: <https://proceedings.mlr.press/v270/kim25c.html>
- Code: <https://github.com/openvla/openvla>

### π₀: a vision-language-action flow model for general robot control (2024)

- Paper: <https://arxiv.org/abs/2410.24164>
- Code: <https://github.com/Physical-Intelligence/openpi>

### π₀.₅: a vision-language-action model with open-world generalization (2025)

- Paper: <https://arxiv.org/abs/2504.16054>
- Code: <https://github.com/Physical-Intelligence/openpi>

### GR00T N1: an open foundation model for generalist humanoid robots (2025)

- Paper: <https://arxiv.org/abs/2503.14734>
- Code: <https://github.com/NVIDIA/Isaac-GR00T>

### Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success (2025)

- Paper: <https://arxiv.org/abs/2502.19645>
- Code: <https://github.com/moojink/openvla-oft>

### EgoScale: scaling dexterous manipulation with diverse egocentric human data (2026)

- Paper: <https://arxiv.org/abs/2602.16710>
- Code: 待补充

### DreamDojo: a generalist robot world model from large-scale human videos (2026)

- Paper: <https://arxiv.org/abs/2602.06949>
- Code: <https://github.com/NVIDIA/DreamDojo>

### Video2Act: a dual-system video diffusion policy with robotic spatio-motional modeling (2025)

- Paper: <https://arxiv.org/abs/2512.03044>
- Code: <https://github.com/jiayueru/Video2Act>（部分发布）

### World action models are zero-shot policies (2026)

- Paper: <https://arxiv.org/abs/2602.15922>
- Code: <https://github.com/dreamzero0/dreamzero>

### MotuBrain: an advanced world action model for robot control (2026)

- Paper: <https://arxiv.org/abs/2604.27792>
- Code: 待补充

<a id="topic-4"></a>

# 4.综述与基础(Surveys & Foundations)

### A survey of embodied world models (2025)

- Paper: 待补充（原目录未提供链接）
- Code: 不适用
- Repository: <https://github.com/tsinghua-fib-lab/Awesome-Embodied-World-Model>

### A comprehensive survey on world models for embodied ai (2025)

- Paper: <https://arxiv.org/abs/2510.16732>
- Code: 不适用
- Repository: <https://github.com/Li-Zn-H/AwesomeWorldModels>

### World model for robot learning: a comprehensive survey (2026)

- Paper: <https://arxiv.org/abs/2605.00080>
- Code: 不适用
- Repository: <https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy>

### The role of world models in shaping autonomous driving: a comprehensive survey (2025)

- Paper: <https://arxiv.org/abs/2502.10498>
- Code: 不适用
- Repository: <https://github.com/LMD0311/Awesome-World-Model>

### Predictive Learning (2016)

- Paper: <https://neurips.cc/archive/2016/Schedule.html>
- Code: 不适用

### The information bottleneck method (2000)

- Paper: <https://arxiv.org/abs/physics/0004057>
- Code: 待补充

### Robotics' End Game: Nvidia's Jim Fan (2026)

- Paper: <https://www.youtube.com/watch?v=3Y8aq_ofEVs>
- Code: 不适用

### DroidRetriever: a transparent and steerable automation system for collaborative mobile information seeking (2026)

- Paper: <https://doi.org/10.1145/3772318.3790396>
- Code: <https://github.com/AkimotoAyako/DroidRetriever>

<a id="topic-5"></a>

# 5.数据集与采集工具(Datasets & Collection)

### Ego4D: around the world in 3,600 hours of egocentric video (2025)

- Paper: <https://arxiv.org/pdf/2110.07058>
- Code: <https://github.com/facebookresearch/Ego4d>（工具 / 基线）

### The Something Something video database for learning and evaluating visual common sense (2017)

- Paper: <https://arxiv.org/pdf/1706.04261>
- Code: 不适用
- Data: <https://www.qualcomm.com/developer/software/something-something-v-2-dataset>（v2）

### Scaling egocentric vision: the EPIC-KITCHENS dataset (2018)

- Paper: <https://arxiv.org/abs/1804.02748>
- Code: <https://github.com/epic-kitchens/epic-kitchens-download-scripts>（工具 / 基线）

### ImageNet Large Scale Visual Recognition Challenge (2015)

- Paper: <https://arxiv.org/pdf/1409.0575>
- Code: <https://image-net.org/challenges/LSVRC/2012/2012-downloads.php>（工具 / 基线）

### The Kinetics Human Action Video Dataset (2017)

- Paper: <https://arxiv.org/pdf/1705.06950>
- Code: <https://github.com/google-deepmind/kinetics-i3d>（工具 / 基线）

### Open X-Embodiment: robotic learning datasets and RT-X models (2023)

- Paper: <https://arxiv.org/abs/2310.08864>
- Code: <https://github.com/google-deepmind/open_x_embodiment>（工具 / 基线）

### DexUMI: using human hand as the universal manipulation interface for dexterous manipulation (2025)

- Paper: <https://arxiv.org/abs/2505.21864>
- Code: <https://github.com/real-stanford/DexUMI>

### OPEN TEACH: a versatile teleoperation system for robotic manipulation (2024)

- Paper: <https://proceedings.mlr.press/v270/iyer25a.html>
- Code: <https://github.com/aadhithya14/Open-Teach>

<a id="topic-6"></a>

# 6.评测与仿真工具(Benchmarks & Simulators)

### WorldArena: a unified benchmark for evaluating perception and functional utility of embodied world models (2026)

- Paper: <https://arxiv.org/abs/2602.08971>
- Code: <https://github.com/tsinghua-fib-lab/WorldArena>

### WorldArena 2.0: extending embodied world model benchmarking on modality, functionality and platform (2026)

- Paper: <https://arxiv.org/pdf/2605.17912>
- Code: <https://github.com/WorldArena2/WorldArena-2.0>

### CALVIN: a benchmark for language-conditioned policy learning for long-horizon robot manipulation tasks (2022)

- Paper: <https://doi.org/10.1109/LRA.2022.3180108>
- Code: <https://github.com/mees/calvin>

### LIBERO: benchmarking knowledge transfer for lifelong robot learning (2023)

- Paper: <https://papers.nips.cc/paper_files/paper/2023/hash/8c3c666820ea055a77726d66fc7d447f-Abstract-Datasets_and_Benchmarks.html>
- Code: <https://github.com/Lifelong-Robot-Learning/LIBERO>

### LIBERO-Plus: in-depth robustness analysis of vision-language-action models (2025)

- Paper: <https://arxiv.org/abs/2510.13626>
- Code: <https://github.com/sylvestf/LIBERO-plus>

### GANs trained by a two time-scale update rule converge to a local Nash equilibrium (2017)

- Paper: <https://proceedings.neurips.cc/paper/2017/hash/8a1d694707eb0fefe65871369074926d-Abstract.html>
- Code: <https://github.com/bioinf-jku/TTUR>

### Towards accurate generative models of video: a new metric and challenges (2018)

- Paper: <https://arxiv.org/abs/1812.01717>
- Code: <https://github.com/google-research/google-research/tree/master/frechet_video_distance>

### MuJoCo: a physics engine for model-based control (2012)

- Paper: <https://doi.org/10.1109/IROS.2012.6386109>
- Code: <https://github.com/google-deepmind/mujoco>


---

[待补充代码](RESOURCE_STATUS.md) · [代码与项目备注](CODE_LINK_AUDIT.md) · [贡献](CONTRIBUTING.md)

排版参考：[Awesome-CVPR2024-Low-Level-Vision](https://github.com/Kobaayyy/Awesome-CVPR2026-CVPR2025-CVPR2024-CVPR2021-CVPR2020-Low-Level-Vision/blob/master/CVPR2024.md)。
