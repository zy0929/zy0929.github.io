---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. student in the School of Biomedical Engineering at Tsinghua University, under the supervision of [Prof. Sen Song](https://scholar.google.com/citations?user=cYgtRP4AAAAJ&hl=zh-CN).

I received my bachelor's degree in Computer Science and Technology from the College of Computer Science and Technology, Zhejiang University, under the supervision of [Prof. Qian Zheng](https://q-zh.github.io/) and [Prof. Zhengxing Huang](https://scholar.google.com/citations?user=uDhL004AAAAJ&hl=en).

My research interests include AI for neuroscience, EEG decoding, and deep learning.

# 🔥 News
- *2026.11*: &nbsp;🎉 Our project wins a **Silver Award** in the **China International College Students’ Innovation Competition (Beijing Division)**! 
- *2026.10*: &nbsp;🎉 Our project is awarded **RMB 200,000** under the **Tsinghua IDG/McGovern “Brain+X” Seed Grant Doctoral and Postdoctoral Program**! 
- *2026.10*: &nbsp;🎉 Our paper "Beyond Isolated Peaks: Point-Aligned RD/RA Context for mmWave Fall Detection" is accepted by **ACM MMAsia**! 
- *2026.09*: &nbsp;🎉 Our paper "Signal-Adaptive Trust Regions for Gradient-Free Optimization of Recurrent Spiking Neural Networks" is accepted by **NeurIPS 2026 (Poster)**! 
- *2026.04*: &nbsp;🎉 Our paper "Training-Driven Representational Geometry Modularization Predicts Brain Alignment in Language Models" is accepted by **CogSci 2026 (Oral)**! 
- *2025.07*: &nbsp;🎉 Our paper "Reward-optimizing learning using stochastic release plasticity" is accepted by **Frontiers in Neural Circuits**!
- *2025.06*: &nbsp;🎉 I receive the **Excellent Undergraduate Dissertation Award** from Zhejiang University!
- *2024.07*: &nbsp;🎉 Our project wins **Second Prize** in the **National Biomedical Engineering Innovation Design Competition**!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/Wireless acquisition core.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A shared wireless acquisition core for cortical and peripheral recordings in freely moving mice](https://www.biorxiv.org/content/10.64898/2026.11.07.764907v1)

Wanmei Zhang<sup>#</sup><sup>†</sup>, Youlang Du<sup>#</sup>, Jiayi Li, Guangyu Liang, Cheng Yi, Mingxiu Cheng, Xinhong Xv, Hao Wang, Hongyu Dong, Sen Song, Yuanlong Zhang, **Zhiyuan Ma<sup>†</sup>**

[![Paper](https://img.shields.io/badge/bioRxiv-2026.11.07.764907-red)](https://www.biorxiv.org/content/10.64898/2026.11.07.764907v1)

- We develop a **lightweight wireless platform** for concurrent **cortical, muscle, and motion recording** in freely moving mice.
- The headstage weighs **1.2 g** (excluding the battery) and achieves **0.176 μV RMS noise** under shorted-input testing over 0.5–100 Hz.
- We demonstrate applications in **neural monitoring** and **behavioral analysis**, with **electrode reassignment** extending the same hardware to cardiac recording.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/LBSNet-complexity.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LBSNet: Lightweight Brain State Modeling via Learnable Spectral Prototypes for EEG-Based Fatigue Detection](https://arxiv.org/abs/2611.11916)

Kun Jia, Zhenyu Cao, Hanlin Yu, Zeyuan Li, Yixuan Liu, Zhongye Xia, Sen Song<sup>†</sup>, **Zhiyuan Ma<sup>†</sup>**

[![Paper](https://img.shields.io/badge/arXiv-2611.11916-red)](https://arxiv.org/abs/2611.11916)
[![GitHub Repo stars](https://img.shields.io/github/stars/zy0929/LBSNet)](https://github.com/zy0929/LBSNet/)

- We propose **LBSNet**, which uses **learnable spectral prototypes** to model local brain states and guide temporal aggregation.
- Across two datasets, LBSNet outperforms **seven baselines**, achieving the **highest** accuracy and F1-score in **subject-independent** fatigue detection.
- With only **1.30K** parameters and **2.89M** MACs, LBSNet reduces parameter count by **98.3%** and computational cost by **89.9%** compared with the strongest baseline on SADT.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/BridgeMIL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking EEG-Based Disease Diagnosis: Decoupling Instance Representation Learning from Subject-Level Supervision](https://arxiv.org/abs/2607.27274)

**Zhiyuan Ma<sup>#</sup>**, Zeyuan Li<sup>#</sup>, Zhiyi Lu<sup>#</sup>, Jiacheng Hao, Youlang Du, Zhen Jiang, Xinche Zhang, Yuhao Sun, Xinke Shen<sup>†</sup>, Sen Song<sup>†</sup>

[![Paper](https://img.shields.io/badge/arXiv-2607.27274-red)](https://arxiv.org/abs/2607.27274)

- We highlight a **fundamental supervision mismatch** in EEG disease diagnosis: **disease labels belong to subjects, not individual EEG windows**.
- We propose **BridgeMIL**, which decouples instance representation learning from subject-level supervision.
- Across **three datasets** and **five backbones**, BridgeMIL ranks first in **14 of 15 settings** and improves mean accuracy by **4.28 percentage points**.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/EEG-JEPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EEG-JEPA: Structured Latent Prediction for EEG Foundation Models](https://arxiv.org/abs/2608.00114)

Jinhao Li<sup>#</sup>, **Zhiyuan Ma<sup>#</sup>**, Xueqiao Han<sup>#</sup>, Zhongye Xia, Xinche Zhang, Shanghong Xie, Yixuan Liu, Yongjian Li, Runmin Gan, Tianlin Huo<sup>†</sup>, Sen Song<sup>†</sup>

[![Paper](https://img.shields.io/badge/arXiv-2608.00114-red)](https://arxiv.org/abs/2608.00114)
[![GitHub Repo stars](https://img.shields.io/github/stars/SWF-hao/EEG-JEPA-official)](https://github.com/SWF-hao/EEG-JEPA-official/)

- We propose **EEG-JEPA**, an EEG foundation model that learns transferable representations through **structured latent prediction**.
- EEG-JEPA ranks **first** on average across **14** frozen-transfer tasks and on all **nine** fine-tuning tasks.
- Layerwise analysis reveals basic signal features in shallow layers and complex interactions in deeper layers.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/DSAINet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DSAINet: An Efficient Dual-Scale Attentive Interaction Network for General EEG Decoding](https://arxiv.org/abs/2604.18095)

**Zhiyuan Ma<sup>#</sup>**, Zeyuan Li<sup>#</sup>, Zihao Qiu<sup>#</sup>, Jinhao Li, Lingqin Meng, Xinche Zhang, Yixuan Liu, Xinke Shen<sup>†</sup>, Sen Song<sup>†</sup>

[![Paper](https://img.shields.io/badge/arXiv-2604.18095-red)](https://arxiv.org/abs/2604.18095)
[![GitHub Repo stars](https://img.shields.io/github/stars/zy0929/DSAINet)](https://github.com/zy0929/DSAINet/)

- We propose **DSAINet**, an efficient dual-scale attentive interaction network for general EEG decoding.
- Comprehensive experiments across **five EEG decoding tasks** and **ten public datasets** show that DSAINet consistently outperforms **13 representative baselines** under subject-independent evaluation, while maintaining the **same architecture and architecture-related hyperparameters** across datasets.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CogSci 2026</div><img src='images/CogSci-2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Training-Driven Representational Geometry Modularization Predicts Brain Alignment in Language Models](https://escholarship.org/uc/item/6c19n50h)

Yixuan Liu<sup>#</sup>, **Zhiyuan Ma<sup>#</sup>**, Likai Tang, Runmin Gan, Xinche Zhang, Jinhao Li, Chao Xie<sup>†</sup>, Sen Song<sup>†</sup>

[![Paper](https://img.shields.io/badge/Paper-CogSci-008B8B)](https://escholarship.org/uc/item/6c19n50h)

- We identify **training-driven geometric modularization** in language models, with **low-complexity layers** better predicting human language-network activity.
- We reveal **distinct brain alignment dynamics** during training: early and stable in temporal regions, but delayed and more dynamic in frontal regions.
- We show that **lower representational curvature** predicts stronger brain alignment beyond training progress, with this relationship becoming more robust in larger models.

</div>
</div>

- `arXiv 2026` [LI-DSN: A Layer-wise Interactive Dual-Stream Network for EEG Decoding](https://arxiv.org/abs/2604.01889), Chenghao Yue<sup>#</sup>, **Zhiyuan Ma<sup>#</sup>**, Zhongye Xia, Xinche Zhang, Yisi Zhang<sup>†</sup>, Xinke Shen<sup>†</sup>, Sen Song<sup>†</sup>
- `NeurIPS 2026` [Signal-Adaptive Trust Regions for Gradient-Free Optimization of Recurrent Spiking Neural Networks](https://arxiv.org/abs/2601.21572), Jinhao Li<sup>#</sup>, Yuhao Sun<sup>#</sup>, **Zhiyuan Ma**, Hao He, Xinche Zhang, Xing Chen, Jin Li<sup>†</sup>, Sen Song<sup>†</sup>
- `arXiv 2026` [Beyond Flattened Tokens: Structure-Preserving EEG Decoding with Reusable TriDim Blocks](https://arxiv.org/abs/2609.19842), Shiyue Su, Song Wang, Zekai Zhan, Junjie Zeng, Ziling Lu, Zongsheng Li, Xinyuan Ye, **Zhiyuan Ma**, Xinke Shen<sup>†</sup>, Quanying Liu<sup>†</sup>
- `Frontiers in Neural Circuits 2025` [Reward-optimizing learning using stochastic release plasticity](https://www.frontiersin.org/journals/neural-circuits/articles/10.3389/fncir.2025.1618506/full), Yuhao Sun<sup>#</sup>, Wantong Liao<sup>#</sup>, Jinhao Li<sup>#</sup>, Xinche Zhang<sup>#</sup>, Guan Wang, **Zhiyuan Ma**, Sen Song<sup>†</sup>

<sup>**†**</sup> denotes corresponding author and <sup>**#**</sup> denotes equal contribution.

# 💰 Fundings
- *2026.10 - 2028.10*, **Tsinghua IDG/McGovern "Brain+X" Seed Grant Doctoral and Postdoctoral Program, RMB 200,000**. 

# 🏆 Awards
- *2026.11*, **Silver Award**, China International College Students’ Innovation Competition (Beijing Division).
- *2026.10*, **Second-Class Comprehensive Excellence Scholarship**, Tsinghua University.
- *2025.06*, **2025 Excellent Undergraduate Dissertation**, Zhejiang University.
- *2024.07*, **Second Prize**, National Biomedical Engineering Innovation Design Competition.

# 📖 Educations
- *2025.08 - now*, Ph.D. Student, Biomedical Engineering, Tsinghua University, Beijing, China. 
- *2021.08 - 2025.06*, Undergraduate, Computer Science and Technology, Zhejiang University, Hangzhou, China.

# 🌏 Academic Service
## Teaching
- *2026 Fall*, **Teaching Assistant**, Technology Innovation and Challenge 2C, Tsinghua University.
- *2026 Spring*, **Teaching Assistant**, Technology Innovation and Challenge 2C, Tsinghua University.
- *2025 Fall*, **Teaching Assistant**, Technology Innovation and Challenge 2C, Tsinghua University.
- *2024 Fall*, **Teaching Assistant**, Computer Organization, Zhejiang University.
- *2024 Spring*, **Teaching Assistant**, Computer Organization, Zhejiang University.

## Journal Reviewer
- IEEE Journal of Biomedical and Health Informatics
- IEEE Transactions on Neural Systems and Rehabilitation Engineering

## Conference Reviewer
- CogSci
- ACM MMAsia
