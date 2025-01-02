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

Currently, I'm a PhD student at the University of Hong Kong (HKU), supervised by [Prof. Hongyang Li](https://lihongyang.info/). My research interests include Humanoid Whole-body Control, 3D Scene Understanding, Human Pose Estimation and Weakly Supervised/Few-shot/Open Vocabulary Object Localization, Detection and Segmentation.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/CD-ViTO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-Domain Few-Shot Object Detection via Enhanced Open-Set Object Detector](https://arxiv.org/abs/2402.03094)

Yuqian Fu*, Yu Wang*, **Yixuan Pan***, Lian Huai, Xingyu Qiu, Tong Liu, Yanwei Fu, Luc Van Gool, Xingqun Jiang

European Conference on Computer Vision (ECCV 2024), co-first author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/rop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rotated Orthographic Projection for Self-Supervised 3D Human Pose Estimation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08803.pdf)

Yao Yao, **Yixuan Pan**, Wenjun Shi, Dongchen Zhu, Lei Wang, Jiamao Li

European Conference on Computer Vision (ECCV 2024), second author

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/tcsvt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Variational Feature Imitation Conditioned on Visual Descriptions for Few-shot Fine-grained Recognition](https://ieeexplore.ieee.org/document/10750049)

Xin Lu, **Yixuan Pan**, Yichao Cao, Xin Zhou, and Xiaobo Lu

IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), second author

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023 Oral</div><img src='images/LCAR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Coarse2Fine: Local Consistency Aware Re-prediction for Weakly Supervised Object Localization](https://ojs.aaai.org/index.php/AAAI/article/view/25292)

**Yixuan Pan**, Yao Yao, Yichao Cao, Chongjin Chen, Xiaobo Lu

Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2023, **oral**), first author 

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🔧 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic Design</div><img src='projects/Simulation of electromagnetic bending gun/gun.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Simulation of electromagnetic bending gun]()

Automatic mark finding by camera and precise targeting

**National First Prize** of National Student Electronic Design Competition (Top 1.8%, total 17,313 teams)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic Design</div><img src='projects/Indoor positioning and tracking of robots/indoor.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Indoor positioning and tracking of robots]()

High-precision indoor positioning and tracking based on UWB

Authorized Patent: An EKF-based multi-sensor fusion greenhouse patrol robot tracking method, first author

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic Design</div><img src='projects/Auto-following robot/car.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Auto-following robot]()

UWB-based following robot

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic Design</div><img src='projects/Greenhouse inspection robot cluster/greenhouse.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Greenhouse inspection robot cluster]()

The inspection vehicle will record the diseased plants according to the camera information, and send it to the spraying vehicle, which will automatically arrive at the recorded location.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronic Design</div><img src='projects/Acousto-optic positioning hexapod disaster relief/light.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Acousto-optic positioning hexapod disaster relief]()

The hexapod robot turns in the direction of the sound source after hearing the target sound, and tracks the light source after recognizing the target light source.

</div>
</div>

# 🎖 Selected Honors and Awards
- National Scholarship (国家奖学金)
- Provincial-Level Merit Student of Jiangsu Province (江苏省三好学生)
- Outstanding Graduates of Jiangsu Province (江苏省优秀毕业生)
- Principal Scholarship (校长奖学金)
- National Student Electronic Design Competition - National First Prize(Top 1.8%, total 17,313 teams)
- "Huawei Cup" The 18th China Post-Graduate Mathematical Contest - National Second Prize
- Artificial Intelligence and Robotics Innovation Competition - National Grand Prize

# 📖 Educations
- *PhD in Embodied AI*, University of Hong Kong. 
- *M.S in Electronic Information (School of Automation)*, Southeast University. 
- *B.S in Electronic Information Engineering*, Jiangsu University, Rank 1/111.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->