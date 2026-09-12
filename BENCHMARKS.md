# 评测与仿真工具 (Benchmarks & Simulators)

[返回首页 / Home](README.md) · [完整列表 / All Papers](WORLD_MODELS.md)

## 目录 (Contents)

- [1. 评测基准 (Benchmarks)](#section-1)
- [2. 评测指标 (Metrics)](#section-2)
- [3. 物理仿真器 (Physics Simulators)](#section-3)

<a id="section-1"></a>

## 1. 评测基准 (Benchmarks)

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


<a id="section-2"></a>

## 2. 评测指标 (Metrics)

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


<a id="section-3"></a>

## 3. 物理仿真器 (Physics Simulators)

### MuJoCo: a physics engine for model-based control (2012)

- Paper: [论文 / Resource](https://doi.org/10.1109/IROS.2012.6386109)
- Code: [GitHub](https://github.com/google-deepmind/mujoco)
- Summary: MuJoCo is a physics engine used to generate and evaluate interactive trajectories.

