
<h1 align="center">
AcadHomepage
</h1>

<div align="center">

[![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/forks/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/issues/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/license/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io/blob/main/LICENSE)  | [中文文档](./docs/README-zh.md) 
</div>

<p align="center">A Modern and Responsive Academic Personal Homepage</p>

<p align="center">
    <br>
    <img src="docs/screenshot.png" width="100%"/>
    <br>
</p>

Some examples:
- [Demo Page](https://rayeren.github.io/acad-homepage.github.io/)
- [Personal Homepage of the author](https://rayeren.github.io/)

## Key Features
- **Automatically update google scholar citations**: using the google scholar crawler and github action, this REPO can update the author citations and publication citations automatically.
- **Support Google analytics**: you can trace the traffics of your homepage by easy configuration.
- **Responsive**: this homepage automatically adjust for different screen sizes and viewports.
- **Beautiful and Simple Design**: this homepage is beautiful and simple, which is very suitable for academic personal homepage.
- **SEO**: search Engine Optimization (SEO) helps search engines find the information you publish on your homepage easily, then rank it against similar websites.

## Quick Start

1. Fork this REPO and rename to `USERNAME.github.io`, where `USERNAME` is your github USERNAME.
1. Configure the google scholar citation crawler:
    1. Find your google scholar ID in the url of your google scholar page (e.g., https://scholar.google.com/citations?user=SCHOLAR_ID), where `SCHOLAR_ID` is your google scholar ID.
    1. Set GOOGLE_SCHOLAR_ID variable to your google scholar ID in `Settings -> Secrets -> Actions -> New repository secret` of the REPO website with `name=GOOGLE_SCHOLAR_ID` and `value=SCHOLAR_ID`.
    1. Click the `Action` of the REPO website and enable the workflows by clicking *"I understand my workflows, go ahead and enable them"*. This github action will generate google scholar citation stats data `gs_data.json` in `google-scholar-stats` branch of your REPO. When you update your main branch, this action will be triggered. This action will also be trigger 08:00 UTC everyday.
1. Generate favicon using [favicon-generator](https://redketchup.io/favicon-generator) and download all generated files to `REPO/images`.
1. Modify the configuration of your homepage `_config.yml`:
    1. `title`: the title of your homepage
    1. `description`: the description of your homepage
    1. `repository`: USER_NAME/REPO_NAME  
    1. `google_analytics_id` (optional): google analytics ID
    1. SEO Related keys (optional): get these keys from search engine consoles (e.g. Google, Bing and Baidu) and paste here.
    1. `author`: the author information of this homepage, including some other websites, emails, city and univeristy.
    1. More configuration details are described in the comments.
1. Add your homepage content in `_pages/about.md`.
    1. You can use html+markdown syntax just same as jekyll.
    1. You can use a `<span>` tag with class `show_paper_citations` and attribute `data` to display the citations of your paper. Set the data to the google scholar paper ID. For
        ```html
        <span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>
        ``` 
        > Q: How to get the google scholar paper ID?   
        > A: Enter your google scholar homepage and click the paper name. Then you can see the paper ID from `citation_for_view=XXXX`, where `XXXX` is the required paper ID.
1. Your page will be published at `https://USERNAME.github.io`.

## Debug Locally

1. Clone your REPO to local using `git clone`.
1. Install Jekyll building environment, including `Ruby`, `RubyGems`, `GCC` and `Make` following [the installation guide](https://jekyllrb.com/docs/installation/#requirements).
1. Run `bash run_server.sh` to start Jekyll livereload server.
1. Open http://127.0.0.1:4000 in your browser.
1. If you change the source code of the website, the livereload server will automatically refresh.
1. When you finish the modification of your homepage, `commit` your changings and `push` to your remote REPO using `git` command.

# Acknowledges

- AcadHomepage incorporates Font Awesome, which is distributed under the terms of the SIL OFL 1.1 and MIT License.
- AcadHomepage is influenced by the github repo [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes), which is distributed under the MIT License.
- AcadHomepage is influenced by the github repo [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io), which is distributed under the MIT License.

<h1 align="center">
  👋 Hi there, I'm Wenjie Zhang (张文捷)
</h1>

<h3 align="center">
  🎓 Master's Student @ Xidian University · 🏙️ Hangzhou, China
</h3>

<p align="center">
  <a href="https://wenj-zhang.github.io/">
    <img src="https://img.shields.io/badge/Homepage-%231DA1F2.svg?style=for-the-badge&logo=homeadvisor&logoColor=white" />
  </a>
  <a href="https://scholar.google.com/citations?user=bKcPnFQAAAAJ&hl=zh-CN">
    <img src="https://img.shields.io/badge/Google%20Scholar-%234285F4.svg?style=for-the-badge&logo=google-scholar&logoColor=white" />
  </a>
  <a href="mailto:wenjiez@stu.xidian.edu.cn">
    <img src="https://img.shields.io/badge/Email-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 📌 About Me

- 🎓 I graduated from the **School of Mechanical and Electronic Information, China University of Geosciences** with a bachelor's degree.
- 🔬 I am currently a **third-year Master's student** at the **Hangzhou Institute for Technology, Xidian University**, under the supervision of Prof. [Bobo Xi](https://b-xi.github.io).
- 🌌 My master's research focuses on **Hyperspectral Image Open-Set Recognition (HSI-OSR)**.
- 🤖 Currently, I am extending my work to **Multimodal Large Language Models (MLLMs)** and **Reinforcement Learning**.
- 🏢 I interned at **Amap (Alibaba)** in Beijing (2025).

---

## 🔥 News

- **2026.02** &nbsp;🎉 One paper accepted by **CVPR 2026**!
- **2025.10** &nbsp;🎉 One paper accepted by **IEEE TIP**!
- **2025.03** &nbsp;🎉 One paper accepted by **IEEE TIP**!

---

## 📝 Selected Publications

### <img src="https://img.shields.io/badge/CVPR%202026-%23FF6F00.svg?style=flat&logo=ieee&logoColor=white" /> SMAP: Semantic Route Planning with Map-Grounded Multimodal Alignment
> **Wenjie Zhang\***, Chen Yang\*, Xin Lu, Zhen Wang, Yue Liu, Bobo Xi, Pengbo Zhang  
> IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2026
> 
> [📄 Paper](https://cvpr.thecvf.com/virtual/2026/poster/39788) · [💻 Code](https://github.com/amap-mobility-intelligence/CVPR_2026_SMAP_Code)


### <img src="https://img.shields.io/badge/IEEE%20TIP%202025-%23007B86.svg?style=flat&logo=ieee&logoColor=white" /> HyperCASR: Spectral-Spatial Open-Set Recognition With Category-Aware Semantic Reconstruction for Hyperspectral Imagery
> Bobo Xi, **Wenjie Zhang**, Jiaojiao Li, Rui Song, Yunsong Li  
> IEEE Transactions on Image Processing (TIP), 2025, 34: 7642-7655  
> [📄 Paper](https://ieeexplore.ieee.org/document/11247869) · [💻 Code](https://github.com/B-Xi/TIP_2025_HyperCASR)

### <img src="https://img.shields.io/badge/IEEE%20TIP%202025-%23007B86.svg?style=flat&logo=ieee&logoColor=white" /> HyperTaFOR: Task-adaptive Few-shot Open-set Recognition with Spatial-Spectral Selective Transformer for Hyperspectral Imagery
> Bobo Xi, **Wenjie Zhang**, Jiaojiao Li, Rui Song, Yunsong Li  
> IEEE Transactions on Image Processing (TIP), 2025, 34: 4148-4160  
> [📄 Paper](https://ieeexplore.ieee.org/document/11071942) · [💻 Code](https://github.com/B-Xi/TIP_2025_HyperTaFOR)

---

## 🎖 Honors & Awards

- **2025.10** &nbsp;🏆 **National Scholarship**, Ministry of Education, China

---

## 📖 Education

| Period | Institution | Degree |
|--------|------------|--------|
| 2023.09 – 2026.06 | Hangzhou Institute for Technology, **Xidian University** | M.E. in Electronic Information |
| 2019.09 – 2023.06 | School of Mechanical and Electronic Information, **China University of Geosciences** | B.E. in Communications Engineering |

---

## 💻 Internship Experience

- **2025.06 – 2025.09** &nbsp;📍 **Amap, Alibaba** — Beijing, China

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=WenJ-Zhang&theme=radical&hide_border=true&area=true" width="95%" />
</p>

---

<p align="center">
  <b>Because it is there.</b> 🏔️
</p>

<p align="center">
  <i>Feel free to connect with me — let's explore the frontiers of AI together!</i>
</p>
