# 表征学习 (Representation)

[返回首页 / Home](README.md) · [完整列表 / All Papers](WORLD_MODELS.md)

## 目录 (Contents)

- [1. 潜在状态与预测表征 (Latent & Predictive Representations)](#section-1)
- [2. 多模态词元表征 (Multimodal Tokenization)](#section-2)
- [3. 结构化世界表征 (Structured Representations)](#section-3)

<a id="section-1"></a>

## 1. 潜在状态与预测表征 (Latent & Predictive Representations)

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


<a id="section-2"></a>

## 2. 多模态词元表征 (Multimodal Tokenization)

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


<a id="section-3"></a>

## 3. 结构化世界表征 (Structured Representations)

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
