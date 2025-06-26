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


I am a M.Eng student at Department of Electrical and Coomputer Engineering, [National University of Singapore](https://nus.edu.sg/), supervised by Prof. [Yueming Jin](https://scholar.google.com/citations?user=s_kbB4oAAAAJ&hl=en). Before that, I received my B.Eng degree from [Harbin Institute of Technology (Shenzhen)](https://www.hitsz.edu.cn/index.html), advised by Prof. [Yongbing Zhang](https://scholar.google.com/citations?user=0KlvTEYAAAAJ&hl=en).

My research interests include computer vision techniques—particularly **image and video segmentation**—and **agentic AI systems**, with a focus on their applications in **medical domains** such as radiology, surgery, and pathology. I have published more than 10 papers at the top conferences and journals with total <a href='https://scholar.google.com/citations?user=fTnoBDAAAAAJ'>google scholar citations <strong><span id='total_cit'>750+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=fTnoBDAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2026.06* &nbsp; <span style="color:red;">Actively seeking Ph.D positions in **medical AI** and **agentic AI** in **2026 Fall**.</span>
If you're interested in collaboration, feel free to reach out!
- *2025.06*: &nbsp;🎉🎉 Our paper "Structure Matters: Revisiting Boundary Refinement in Video Object Segmentation" has been accepted by ICCV 2025.
- *2025.05*: &nbsp;🎉🎉 Our paper "ReSurgSAM2: Referring Segment Anything in Surgical Video via Credible Long-term Tracking" has been early accepted by MICCAI 2025 (top 9%). 
- *2025.04*: &nbsp;🎉🎉 Our paper "The Four Color Theorem for Cell Instance Segmentation" has been accepted by ICML 2025. 
- *2025.03*: &nbsp;🎉🎉 Our paper "Seine: Structure encoding and interaction network for nuclei instance segmentation" has been accepted by IEEE JBHI. 
- *2025.02*: &nbsp;🎉🎉 Our paper "Medical sam adapter: Adapting segment anything model for medical image segmentation" has been accepted by MedIA. 
- *2024.12*: &nbsp;🎉🎉 Our paper "Multi-scale Context Intertwining for Panoramic Renal Pathology Segmentation" has been accepted by ICASSP 2025. 
- *2024.12*: &nbsp;🎉🎉 Our paper "Dawn: Domain-adaptive weakly supervised nuclei segmentation via cross-task interactions" has been accepted by IEEE TCSVT. 
- *2024.5*: &nbsp;🎉🎉 Our paper "Dynamic pseudo label optimization in point-supervised nuclei segmentation" has been early accepted by MICCAI 2024 (top11%).
- *2024.2*: &nbsp;🎉🎉 Our paper "Boundary-aware Contrastive Learning for Semi-supervised Nuclei Instance Segmentation" has been accepted by MIDL 2024 (Oral).


# 📝 Selected Publications 

<!-- ### 1 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/papers/map.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Medagent-pro: Towards evidence-based multi-modal medical diagnosis via reasoning agentic workflow](https://arxiv.org/pdf/2503.18968)

**Ziyue Wang**, Junde Wu, Linghan Cai, Chang Han Low, Xihong Yang, Qiaxuan Li, Yueming Jin

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We present an evidence-based reasoning agentic system with both quantitative and qualitative evidence for explainable medical diagnosis.
</div>
</div>

<!-- ### 2 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/papers/surgraw.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Surgraw: Multi-agent workflow with chain-of-thought reasoning for surgical intelligence](https://arxiv.org/pdf/2503.10265)

Chang Han Low, **Ziyue Wang**, Tianyi Zhang, Zhitao Zeng, Zhuo Zhu, Evangelos B. Mazomenos, Yueming Jin
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We present a CoT-driven multi-agent framework for accurate and interpretable analysis of surgical vision tasks.
</div>
</div>

<!-- ### 2 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV25</div><img src='images/papers/oasis.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Structure Matters: Revisiting Boundary Refinement in Video Object Segmentation](https://shinning0821.github.io/)

Guanyi Qin, **Ziyue Wang**, Daiyun Shen, Haofeng Liu, Hantao Zhou, Junde Wu, Runze Hu, Yueming Jin
# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel boundary amendment video object segmentation method with inherent structure refinement
</div>
</div>

<!-- ### 3 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MedIA (IF=10.7)</div><img src='images/papers/msa.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Medical sam adapter: Adapting segment anything model for medical image segmentation](https://www.sciencedirect.com/science/article/pii/S1361841525000945)

Junde Wu, **Ziyue Wang**, Mingxuan Hong, Wei Ji, Huazhu Fu, Yanwu Xu, Min Xu, Yueming Jin
# <strong><span class='show_paper_citations' data='fTnoBDAAAAAJ:_Qo2XoVZTnwC'></span></strong>
- We present a simple yet effective adaptation technique, to extend SAM to medical domain.
- Received over **600** citations on google scholar.
</div>
</div>

<!-- ### 5 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI25 (CCF-B)</div><img src='images/papers/donu.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic pseudo label optimization in point-supervised nuclei segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_21)

**Ziyue Wang**, Ye Zhang, Yifeng Wang, Linghan Cai, Yongbing Zhang
# <strong><span class='show_paper_citations' data='fTnoBDAAAAAJ:iH-uZ7U-co4C'></span></strong>
- We present a framework leverage CAM to achieve accurate weak-supervised nuclei segmentation.
</div>
</div>

<!-- ### 6 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MIDL24 (Oral)</div><img src='images/papers/bass.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boundary-aware Contrastive Learning for Semi-supervised Nuclei Instance Segmentation](https://proceedings.mlr.press/v250/zhang24a.html)

Ye Zhang, **Ziyue Wang**, Yifeng Wang, Hao Bian, Linghan Cai, Hengrui Li, Lingbo Zhang, Yongbing Zhang
# <strong><span class='show_paper_citations' data='fTnoBDAAAAAJ:YsMSGLbcyi4C'></span></strong>
- We proposes a boundary-aware contrastive learning network to denoise the boundary noise for semi-supervised nuclei segmentation.
</div>
</div>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

- [ReSurgSAM2: Referring Segment Anything in Surgical Video via Credible Long-term Tracking](https://arxiv.org/pdf/2505.08581) Haofeng Liu, Mingqi Gao, Xuxiao Luo, Ziyue Wang, Guanyi Qin, Junde Wu, Yueming Jin, **MICCAI 2025**
- [Seine: Structure encoding and interaction network for nuclei instance segmentation](https://ieeexplore.ieee.org/abstract/document/10980302), Ye Zhang, Linghan Cai, Ziyue Wang, Yongbing Zhang,  **IEEE JBHI**

# 🎖 Honors and Awards
- *2023.10* Second-class academic schorlarship of undergraduate (top 10%).
- *2022.10* Second-class academic schorlarship of undergraduate (top 10%).
- *2022.10* 11th of the NeurIPS22 Cellseg challenge among 500 teams, Paper [here](https://proceedings.mlr.press/v212/wang23a.html)
- *2022.6* 11th of the MIDOG2022 challenge of MICCAI2023, Paper [here](https://www.sciencedirect.com/science/article/pii/S136184152400080X)


# 📖 Educations
- *2024.08 - 2026.06 (now)*, M.Eng. Student (Master by Research) at Department of Electrical and Coomputer Engineering, National University of Singapore, supervised by Prof. Yueming Jin. 
- *2020.09 - 2024.07*, B.Eng. Student at Department of Computer Science and Technology, Harbin Institute of Technology (Shenzhen), supervised by Prof. Yongbing Zhang.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2021.10 - 2024.06*, Research Assistant in Harbin Institute of Technology (Shenzhen) and Tsinghua Shenzhen International Graduate School, supervised by Prof. Yongbing Zhang.