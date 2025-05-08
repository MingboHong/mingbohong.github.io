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

I am a first-year Ph.D. student at the University of Twente, advised by [Hao Cheng](https://scholar.google.de/citations?user=oHK-JSUAAAAJ&hl=en), [Caroline Gevaert](https://scholar.google.nl/citations?user=ab_tGL4AAAAJ&hl=en), and [George Vosselman](https://scholar.google.nl/citations?user=ro6HQUIAAAAJ&hl=en).
Prior to this,
I was a researcher at Megvii Technology, supervised by [Prof.Shuaicheng Liu](http://www.liushuaicheng.org/). I received my Master's degree from Sichuan University in 2022, supervised by [Prof.Qijun Zhao](http://www.scubrl.org/qjzhao). 
I also received my Bachelor's degree from Sichuan Agricultural University in 2019.

During the Megvii,  I was luckily mentored by [Shen Cheng](https://scholar.google.com/citations?user=gBE3HvwAAAAJ&hl=en), [Haipeng Li](https://lhaippp.github.io/), and [Nianjin Ye](https://scholar.google.com/citations?user=AhwGG78AAAAJ&hl=zh-CN).

My research interests include image alignment and object detection. Find more detailed information in my [CV](https://drive.google.com/file/d/1qSZYsBv1il37LwWUyprQfygkPF6lldks/view?usp=drive_link)

I have published several papers at conferences and journals, including CVPR, ECCV, NeurIPS, AAAI, IEEE TPAMI, IEEE TCSVT, etc. My publication received a total <a href='https://scholar.google.com/citations?user=6DpdNBkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> citations.

# 🔥 News
- *2025.04*: 🎉 One paper is accepted by IEEE TCSVT
- *2024.12*: 🎉 One paper is accepted by AAAI 2025
- *2024.11*: 🎉 One paper is accepted by IEEE TPAMI
- *2024.09*: 🎉 One paper is accepted by NeurIPS 2024
- *2024.07*: 🎉 One paper is accepted by ECCV 2024


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div class="badge">IEEE TCSVT </div><img src='images/RSdiffuser.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Multi-Frame Rolling Shutter Correction with Diffusion Models**

Zhanglei Yang, Haipeng Li, Shen Cheng, **Mingbo Hong**, Bing Zeng, Shuaicheng Liu

[Paper](https://ieeexplore.ieee.org/abstract/document/10965711)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:W7OEmFMy1HYC'></span></strong> 

[![](https://img.shields.io/github/stars/lhaippp/DM-RSC?style=social&label=DM-RSC Stars)](https://github.com/lhaippp/DM-RSC)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div class="badge">AAAI 2025 </div><img src='images/RSdiffuser.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Single Image Rolling Shutter Removal with Diffusion Models**

Zhanglei Yang, Haipeng Li, **Mingbo Hong**, Jiajun Li, Bing Zeng,  Shuaicheng Liu

[Paper](https://arxiv.org/pdf/2407.02906)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:UeHWp8X0CEIC'></span></strong> 

[![](https://img.shields.io/github/stars/lhaippp/RS-Diffusion?style=social&label=RS-Diffusion Stars)](https://github.com/lhaippp/RS-Diffusion)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div class="badge">IEEE TPAMI </div><img src='images/MeshHomo.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Unsupervised Global and Local Homography Estimation with Coplanarity-Aware GAN**

Shuaicheng Liu, **Mingbo Hong**, Yuhang Lu, Nianjin Ye, Chunyu Lin, Bing Zeng

[Paper](https://ieeexplore.ieee.org/abstract/document/10772056/)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:u5HHmVD_uO8C'></span></strong> 

[![](https://img.shields.io/github/stars/megvii-research/HomoGAN?style=social&label=HomoGAN Stars)](https://github.com/megvii-research/HomoGAN)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div class="badge">NeurIPS 2024</div><img src='images/yola.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**You Only Look Around: Learning Illumination-Invariant Feature for Low-light Object Detection**

**MingboHong**, Shen Cheng, Haibin Huang, Haoqiang Fan, Shuaicheng Liu 

[Paper](https://arxiv.org/abs/2410.18398)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:IjCSPb-OGe4C'></span></strong> 

[![](https://img.shields.io/github/stars/MingboHong/YOLA?style=social&label=YOLA Stars)](https://github.com/MingboHong/YOLA)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">ECCV 2024</div><img src='images/eccv_2024.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Neural Spectral Decomposition for Dataset Distillation**

Shaolei Yang, Shen Cheng, **Mingbo Hong**, Haoqiang Fan, Xing Wei, Shuaicheng Liu

[Paper](https://arxiv.org/abs/2408.16236)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:IjCSPb-OGe4C'></span></strong> 

[![](https://img.shields.io/github/stars/slyang2021/NSD?style=social&label=NSD Stars)](https://github.com/slyang2021/NSD)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div class="badge">CVPR 2022</div><img src='images/HomoGAN.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Unsupervised Homography Estimation with Coplanarity-Aware GAN**

**Mingbo Hong**, Yuhang Lu, Nianjin Ye, Chunyu Lin, Qijun Zhao, Shuaicheng Liu

[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Hong_Unsupervised_Homography_Estimation_With_Coplanarity-Aware_GAN_CVPR_2022_paper.pdf)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:u5HHmVD_uO8C'></span></strong> 


[![](https://img.shields.io/github/stars/megvii-research/HomoGAN?style=social&label=HomoGAN Stars)](https://github.com/megvii-research/HomoGAN)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">IEEE GRSL 2021</div><img src='images/sspnet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**SSPNet: Scale Selection Pyramid Network for Tiny Person Detection from UAV Images** (*<span style="color: red;">Included in Google Scholar's H5-indexed list</span>*)

**Mingbo Hong**, Shuiwang Li, Yuchao Yang, Feiyu Zhu, Qijun Zhao, Li Lu

[Paper](https://arxiv.org/abs/2107.01548)<strong><span class='show_paper_citations' data='6DpdNBkAAAAJ:9yKSN-GCB0IC'></span></strong> 

[![](https://img.shields.io/github/stars/MingboHong/SSPNet?style=social&label=SSPNet Stars)](https://github.com/MingboHong/SSPNet)

</div>
</div>


# 🎖 Honors and Awards
- *2022.05* Distinguished Graduation Thesis of Sichuan University 
- *2022.06* Outstanding Graduate Student of Sichuan University 


# 🗺️ Visitor Map

<div style="width: 400px; height: 300px;">
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=8Gd6LyQX6ZUDXXq9zxO9WALJVhlrUU9-VtoyJ-_g53Y&cl=ffffff&w=a"></script>
</div>

