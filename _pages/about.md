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

My name is Lin Zhu. I received a B.S. degree in Statistics from Central South University, China, in 2019 and an M.S. degree in Statistics from Shandong University, China, in 2022. Now, I am currently pursuing a PhD degree in Computer Science and Technology at Shanghai Jiao Tong University, China, where I was advised by Prof.[Nanyang Ye](https://ynysjtu.github.io/).

My research interests include Multimodal Perception and Reasoning, Trustworthy AI, and Out-of-Distribution Generalization. I have published several papers on top machine learning journals and conferences, including TPAMI, IJCV, NeurIPS, ICML, ICLR, and AAAI.



# 🔥 Recent Updates

- *2026.01*: One journal paper [CFSM](https://ieeexplore.ieee.org/abstract/document/11345458) accepted to TPAMI. 
- *2025.08*:  One journal paper [InfoBound](https://ieeexplore.ieee.org/abstract/document/11112669) accepted to TPAMI.  
- *2025.09*:  One conference paper [DeltaEnergy](https://arxiv.org/pdf/2510.11296) accepted to NeurIPS2025. 
- 2025.07:  One extended paper [Bayes-CAL](https://link.springer.com/article/10.1007/s11263-025-02527-y) accepted to IJCV.  
- 2025.03:  One conference paper [OODD](https://openaccess.thecvf.com/content/CVPR2025/papers/Yang_OODD_Test-time_Out-of-Distribution_Detection_with_Dynamic_Dictionary_CVPR_2025_paper.pdf) accepted to CVPR2025.  
- *2025.01*:  One conference paper [MaskST](https://arxiv.org/pdf/2502.07466) accepted to ICLR2025. 
- *2024.05*:  One conference paper [CRoFT](https://arxiv.org/pdf/2405.16417) accepted to ICML2024. 
- *2024.04*:  One journal paper [OoD-Control](https://ieeexplore.ieee.org/abstract/document/10510598) accepted to TPAMI. 
- *2024.02*:  One journal paper [VLAD](https://link.springer.com/article/10.1007/s11263-024-02036-4) accepted to IJCV. 
- *2023.12*:  Two conference papers [Bayes-CAL](https://ojs.aaai.org/index.php/AAAI/article/view/26355) and [SDL](https://ojs.aaai.org/index.php/AAAI/article/view/26295) accepted to AAAI2023. 



# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/infobound.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[InfoBound: A Provable Information-Bounds Inspired Framework for Both OoD Generalization and OoD Detection](https://ieeexplore.ieee.org/abstract/document/11112669)

**Lin Zhu**, Yifeng Yang, Zichao Nie, Yuan Gao, Jiarui Li, Qinying Gu, Xinbing Wang, Chenghu Zhou, Nanyang Ye

This paper addresses real-world scenarios where covariate shifts and semantic shifts coexist, proposing a unified information-theoretic framework to improve both OoD generalization and OoD detection. By combining Mutual Information Minimization (MI-Min) and Conditional Entropy Maximization (CE-Max), the method mitigates the trade-off between the two tasks and achieves superior performance on multi-label image classification and object detection.
</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI</div><img src='images/cfsm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[CFSM: A Novel Causal Feature Selection Module for Two-Dimensional Out-of-Distribution Generalization](https://ieeexplore.ieee.org/abstract/document/11345458)

**Lin Zhu**, Weihan Yin, Yiyao Yang, Yifei Wu, Qinying Gu, Xinbing Wang, Chenghu Zhou, Nanyang Ye

This paper identifies the limitations of existing causality-inspired OOD generalization methods, which mainly treat domain differences as confounders but may overlook complex spurious correlations in real-world data. To address this, the authors propose a modified causal intervention framework with a Causal Feature Selection Module (CFSM), which suppresses both domain-difference and spurious-correlation features, leading to improved two-dimensional OOD generalization performance.

</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2025</div><img src='images/maskst.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Less is more: Masking elements in image condition features avoids content leakages in style transfer diffusion models](https://arxiv.org/abs/2502.07466)

**Lin Zhu**, Xinbing Wang, Chenghu Zhou, Qinying Gu, Nanyang Ye

This paper addresses content leakage in style-reference-based text-to-image diffusion models, where reference images unintentionally transfer their content along with style. The authors propose a training-free masking strategy that drops selected image-feature elements from the style reference, showing that fewer but better-chosen conditions can improve content-style disentanglement and enhance style transfer performance.

</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV</div><img src='images/bayescal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Bayes-CAL: Robust Cross-Modal Alignment by Bayesian Approach for Few-Shot OoD Generalization](https://link.springer.com/article/10.1007/s11263-025-02527-y)

**Lin Zhu**, Weihan Yin, Fan Wu, Qinying Gu, Xinbing Wang, Chenghu Zhou, Nanyang Ye

This paper studies few-shot two-dimensional OoD generalization under both correlation shift and diversity shift, where fine-tuned large pre-trained models may overfit limited samples and generalize poorly to unseen classes. The authors propose Bayes-CAL, a Bayesian cross-modal image-text alignment method that fine-tunes text representations with domain-invariant regularization, achieving stronger and more stable OoD performance across image classification, object detection, and instance segmentation.

</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2025</div><img src='images/deltaenergy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[ΔEnergy: Optimizing Energy Change During Vision-Language Alignment Improves both OOD Detection and OOD Generalization](https://arxiv.org/pdf/2510.11296)

**Lin Zhu**, Yifeng Yang, Xinbing Wang, Qinying Gu, Nanyang Ye

This paper proposes ΔEnergy, a new OOD score for vision-language models that better distinguishes semantic-shifted OOD samples by measuring energy changes after vision-language re-alignment. Based on ΔEnergy, the authors develop a unified fine-tuning framework that improves both OOD detection and covariate-shift OOD generalization, achieving substantial AUROC gains over recent methods.

</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML2024</div><img src='images/croft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[CRoFT: Robust Fine-Tuning with Concurrent Optimization for OOD Generalization and Open-Set OOD Detection](https://arxiv.org/pdf/2405.16417)

**Lin Zhu**, Yifeng Yang, Qinying Gu, Xinbing Wang, Chenghu Zhou, Nanyang Ye

This paper studies how to fine-tune vision-language pre-trained models while preserving their ability to generalize under covariate shifts and detect semantic-shifted unseen classes. The authors propose a unified fine-tuning objective based on minimizing the gradient magnitude of energy scores, which theoretically promotes domain-consistent Hessians and empirically improves both OOD generalization and OOD detection.

</div>
</div>

# 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV</div><img src='images/vlad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Vision-Language Alignment Learning Under Affinity and Divergence Principles for Few-Shot Out-of-Distribution Generalization](https://arxiv.org/pdf/2405.16417)

**Lin Zhu**, Weihan Yin, Yiyao Yang, Fan Wu, Zhaoyu Zeng, Qinying Gu, Xinbing Wang, Chenghu Zhou, Nanyang Ye

This paper proposes VLAD, a vision-language alignment framework for robust few-shot OOD generalization by using frozen CLIP language embeddings as invariant anchors and adapting visual features through lightweight adapters. By introducing affinity and divergence regularization, VLAD enhances class discrimination, suppresses non-causal features, and provides theoretical and empirical evidence for tighter OOD generalization bounds under distribution shifts.

</div>
</div>



# 📑 Working Papers

Adaptive Visual Evidence-Guided Decoding for Hallucination Reduction in LVLMs.

∆Energy++: Optimizing Energy Changes for Improved Robustness across Vision–Language Models.

ATT-COT: Prompting Vision-Language Models for OOD Generalization via Attention-Aware Chain-of-Thought.



# 🎖 Honors and Awards

- **National Scholarship for Postgraduate Students**, 2025
- **NeurIPS Top Reviewer**, 2025
- **Huatai Securities Technology Scholarship**, Shanghai Jiao Tong University, 2024
- **Outstanding Graduates**, ShanDong University, 2022



## ✔︎ Professional Activities

#### Reviewers

- [IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)](http://cvpr2025.thecvf.com/)
- [International Conference on Machine Learning (ICML)](https://icml.cc/)
- [International Conference on Learning Representations (ICLR)](https://www.iclr.cc/Conferences/2025)
- [Neural Information Processing Systems (NeurIPS)](https://neurips.cc/Conferences/2025)
- [The IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)](https://wacv2025.thecvf.com/)
- [The British Machine Vision Conference (BMVC)](https://www.bmva.org/bmvc)

