# 世界模拟 (Simulation)

[返回首页 / Home](README.md) · [完整列表 / All Papers](WORLD_MODELS.md)

## 目录 (Contents)

- [1. 潜在动力学 (Latent Dynamics)](#section-1)
- [2. 视频与交互生成 (Video & Interactive Generation)](#section-2)
- [3. 三维世界与数据生成 (3D Worlds & Data Generation)](#section-3)

<a id="section-1"></a>

## 1. 潜在动力学 (Latent Dynamics)

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


<a id="section-2"></a>

## 2. 视频与交互生成 (Video & Interactive Generation)

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


<a id="section-3"></a>

## 3. 三维世界与数据生成 (3D Worlds & Data Generation)

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
