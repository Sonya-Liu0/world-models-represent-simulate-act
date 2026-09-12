# 数据集与采集工具 (Datasets & Collection)

[返回首页 / Home](README.md) · [完整列表 / All Papers](WORLD_MODELS.md)

## 目录 (Contents)

- [1. 数据集 (Datasets)](#section-1)
- [2. 数据采集接口 (Data Collection Interfaces)](#section-2)

<a id="section-1"></a>

## 1. 数据集 (Datasets)

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


<a id="section-2"></a>

## 2. 数据采集接口 (Data Collection Interfaces)

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
