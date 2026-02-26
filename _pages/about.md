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

Hi there, I am Wenjie Zhang (Chinese name: 张文捷). I graduated from the School of Mechanical and Electronic Information, China University of Geosciences with a bachelor’s degree, and I am currently a third-year Master’s student  from the Hangzhou Institute for Technology, Xidian University, under the supervision of Prof. Bobo Xi.

My master’s research primarily focused on Hyperspectral Image Open-Set Recognition (HSI-OSR). Currently, I am extending my work to Multimodal Large Language Models (MLLMs) and Reinforcement Learning. You can find my Google Scholar profile here: <a href='https://scholar.google.com/citations?user=bKcPnFQAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 One paper was accepted by CVPR 2026.
- *2025.10*: &nbsp;🎉🎉 One paper was accepted by IEEE TIP.
- *2025.03*: &nbsp;🎉🎉 One paper was accepted by IEEE TIP.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/SMAP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SMAP: Semantic Route Planning with Map-Grounded Multimodal Alignment. **Zhang Wenjie\***, Yang Chen\*, Lu Xin, Wang Zhen, Liu Yue, Xi Bobo, Zhang Pengbo. IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2026. **HTML**

<!-- <small>\* Equal contribution / 共同第一作者</small> -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=bKcPnFQAAAAJ) <strong><span class='show_paper_citations' data='bKcPnFQAAAAJ'></span></strong> -->
- SMAP is the first multimodal framework for semantic route planning that reduces geographical hallucinations via a novel self-editing pipeline. 
</div>
</div>

- [HyperCASR: Spectral-Spatial Open-Set Recognition With Category-Aware Semantic Reconstruction for Hyperspectral Imagery](https://ieeexplore.ieee.org/document/11247869). Xi, Bobo, **Zhang Wenjie**, Li Jiaojiao, Song Rui, Li Yunsong. IEEE Transactions on Image Processing (IEEE TIP), 2025, 34: 7642-7655. [CODE](https://github.com/WenJ-Zhang/TIP_2025_HyperCASR)

- [HyperTaFOR: Task-adaptive few-shot open-set recognition with spatial-spectral selective transformer for hyperspectral imagery](https://ieeexplore.ieee.org/document/11071942). Xi, Bobo, **Zhang Wenjie**, Li Jiaojiao, Song Rui, Li Yunsong. IEEE Transactions on Image Processing (IEEE TIP), 2025, 34: 4148-4160. [CODE](https://github.com/WenJ-Zhang/TIP_2025_HyperTaFOR)


# 🎖 Honors and Awards
- *2025.10* 2025 National Scholarship, Ministry of Education, China. 

# 📖 Educations
- *2023.09 - 2026.06*, Master of Electronic Information, Hangzhou Institute for Technology, Xidian University, Xi'an, China.
- *2019.09 - 2023.06*, Bachelor of Communications Engineering, School of Mechanical and Electronic Information, China University of Geosciences, Wuhan, China. 

# 💻 Internships
- *2025.06 - 2025.09*, Amap, Alibaba, Beijing, China.