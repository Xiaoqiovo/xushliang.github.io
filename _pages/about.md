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

# 👋 About Me

I am a PhD student at **City University of Hong Kong** and **Shenzhen Loop Area Institute**, starting in September 2025. My research is centered on the intersection of multi-modal learning and surgical intelligence. I have been deeply involved in developing large-scale clinical AI systems and optimizing foundation models for medical applications.

### 🔍 Research Interests
* **Multi-modal Learning**: Vision-Language Models (VLMs), Cross-modal Alignment, and Long-video Understanding.
* **World Models**: Generative World Models for video prediction and spatio-temporal consistency.
* **Test-Time Adaptation (TTA)**: Efficient adaptation for long-context learning.
* **Medical AI**: Intelligent analysis for laryngoscopy and respiratory intensive care.

I am currently a Research Assistant at **CAIR, HKISI-CAS**, where I lead projects on intelligent laryngoscopy systems and multi-agent clinical pathways.

<a href='https://scholar.google.com/citations?user=PkvoXRwAAAAJ'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Three papers (MCDRL, F²-Assist, ReGenHOI) were accepted by **CVPR 2026**!
- *2025.03*: &nbsp;🚀 We released the "**Qilu-Jingjie**" Laryngoscope Diagnostic Large Model.
- *2024.12*: &nbsp;📝 Our work on inpatient pathways was published in **npj Health Systems**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/medical_seg.png' alt="MCDRL" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MCDRL: Multimodal Causality-Driven Representation Learning for Generalizable Medical Image Segmentation](https://scholar.google.com/citations?user=PkvoXRwAAAAJ)

**Xusheng Liang**, Lihua Zhou*, Nianxin Li, Miao Xu, Ziyang Song, Dong Yi, Jinlin Wu, Jiawei Ma, et al.

- This work introduces a causality-driven approach to align multimodal medical data, significantly improving the generalization of segmentation models across different clinical centers.
</div>
</div>

- *$F^{2}$-Assist: Multi-Phase Fetal Growth Forecast and Report Generation from Ultrasound Examination*, Bin Pu, **Xusheng Liang**, Xinpeng Ding, et al., **CVPR 2026**
- *ReGenHOI: Unifying Reconstruction and Generation for 3D Human-Object Interaction Understanding*, Miao Xu, ..., **Xusheng Liang**, et al., **CVPR 2026**
- *MAP: Evaluation and Multi-Agent Enhancement of Large Language Models for Inpatient Pathways*, Zhen Chen, ..., **Xusheng Liang**, et al., **npj Health Systems**

# 🎖 Honors and Awards
- *2019-2022* **Pacesetter Scholarship** (Top 5%), Awarded for three consecutive years.
- *2025.03* Core Contributor to the "Qilu Jingjie" Laryngoscope Diagnostic Large Model.

# 📖 Educations
- *2025.09 - Present*, Joint PhD in Computer Science, **City University of Hong Kong & Shenzhen Loop Area Institute**.
- *2023.09 - 2024.06*, M.Sc. in Biomedical Engineering, **City University of Hong Kong**.
- *2019.09 - 2023.06*, B.Sc. in Biomedical Engineering, **University of Electronic Science and Technology of China (UESTC)**.

# 💻 Experience
- *2023.07 - Present*, **Research Assistant**, CAIR, HKISI-CAS, Hong Kong.
  - Developed the "Qilu-Jingjie" MLLM for real-time laryngoscopy analysis (96.4% accuracy).
  - Optimized InternVL for automatic medical report generation, reducing writing time by 80%.
