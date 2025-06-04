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

I'm a second-year undergraduate student at [HKUST(GZ)](https://www.hkust-gz.edu.cn/), majoring in Artificial Intelligence. I'm also a member of [Envision Lab](https://envision-research.hkust-gz.edu.cn/), with privilege of working closely with [Dongyu Yan](http://me.starydy.xyz/), [Tianshuo Xu](https://scholar.google.com/citations?user=I6_dXvEAAAAJ&hl=zh-CN), [Zhifei Chen](https://scholar.google.com/citations?user=RZv77XwAAAAJ&hl=en) and under the guidance of Prof.[Ying-Cong Chen](https://www.yingcong.me/). My research interests mainly focus on generative models including 3D generation, texture generation and video generation. 
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 Our Paper [FlexPainter: Flexible and Multi-View Consistent Texture Generation](https://arxiv.org/pdf/2506.02620) is released.
- *2025.02*: &nbsp;🎉🎉 Our Paper [Kiss3DGen: Repurposing Image Diffusion Models for 3D Asset Generation](https://www.arxiv.org/pdf/2503.01370) is accepted by CVPR2025.
- *2025.02*: &nbsp;🎉🎉 Our Paper [Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/abs/2412.15050) is accepted by CVPR2025.
- *2024.12*: &nbsp;🎉🎉 Our Paper [Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/abs/2412.15050) is released.
- *2024.12*: &nbsp;🎉🎉 Our paper [Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/abs/2412.00547) is released. 

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/flexpainter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[[Kiss3DGen: Repurposing Image Diffusion Models for 3D Asset Generation](https://arxiv.org/pdf/2506.02620)]

Dongyu Yan$^{\star}$, **Leyi Wu$^{\star}$**, Jiantao Lin, Luozhou Wang, Tianshuo Xu, Zhifei Chen, Zhen Yang, Lie Xu, Shunsi Zhang, Ying-Cong Chen$^{\dagger}$
* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/pdf/2506.02620) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project Page**](https://starydy.xyz/FlexPainter/) <strong></strong>
[**Code**](https://github.com/StarRealMan/FlexPainter) <strong></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR2025</div><img src='images/kiss3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Kiss3DGen: Repurposing Image Diffusion Models for 3D Asset Generation](https://www.arxiv.org/pdf/2503.01370)

Jiantao Lin$^{\star}$, Xin Yang$^{\star}$, Meixi Chen$^{\star}$, Yingjie Xu, Dongyu Yan, **Leyi Wu**, Xinli Xu, Lie Xu, Shunsi Zhang, Ying-Cong Chen$^{\dagger}$
* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://www.arxiv.org/pdf/2503.01370) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project Page**](https://ltt-o.github.io/Kiss3dgen.github.io/) <strong></strong>
[**Code**](https://github.com/EnVision-Research/Kiss3DGen) <strong></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR2025</div><img src='images/uni_renderer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/pdf/2412.15050)

Zhifei Chen$^{\star}$, Tianshuo Xu$^{\star}$, Wenhang Ge$^{\star}$, **Leyi Wu**, Dongyu Yan, Jing He, Luozhou Wang, Lu Zeng, Shunsi Zhang, Yingcong Chen$^{\dagger}$
* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/pdf/2412.15050) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/EnVision-Research/Uni-Renderer) <strong></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/motion_dreamer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/pdf/2412.00547)

Tianshuo Xu$^{\star}$, Zhifei Chen$^{\star}$, **Leyi Wu**, Hao Lu, Yuying Chen, Lihui Jiang, Bingbing Liu, Yingcong Chen$^{\dagger}$

* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/pdf/2412.00547) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**](https://github.com/EnVision-Research/MotionDreamer) <strong></strong>
</div>
</div>

# 🎖 Honors and Awards
- **Gold Medal**, The 16th place  
  *Huawei Cup The 2023* **ICPC Asia-East Continent Final Contest**  
  Shanghai, China | 2024

- **Silver Medal**  
  *The 2023* **ICPC Asia Hefei Regional Contest**  
  Hefei, China | 2023

- **Silver Medal**  
  *The 48th* **ICPC Asia Regional Contest Jinan Site**  
  Jinan, China | 2023

- **Silver Medal**  
  *2023* **China Collegiate Programming Contest (CCPC), Shenzhen Site**  
  Shenzhen, China | 2023

- **Bronze Medal**  
  *2023* **China Collegiate Programming Contest (CCPC), Harbin Site**  
  Harbin, China | 2023

- **Dean's List Award for Fall 2023 - 2024**  
  HKUST(GZ) | 2024

- **Dean's List Award for Spring 2024 - 2025**  
  HKUST(GZ) | 2024

- **Dean's List Award for Fall 2024 - 2025**  
  HKUST(GZ) | 2025

# 📖 Educations
- *2023.08 - 2025.02 (now)*, Bachelor of Artificial Intelligence, [HKUST(GZ)](https://www.hkust-gz.edu.cn/). 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
