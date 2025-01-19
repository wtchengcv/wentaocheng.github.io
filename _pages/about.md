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

# 👨‍💻 About Me
<!-- I will join <a href="https://www.uic.edu.cn/en/">**UIC**</a> as an Associate Professor in February 2025.  -->

I used to be an Associate Professor in College of Computer Science, Nankai University. Before that, I was a senior algorithm engineer and a senior product manager in Alibaba Group, where I mainly worked on a perception system for autonomous vehicles. 


I earned my Ph.D. from Nanyang Technological University, working under the supervision of <a href='https://personal.ntu.edu.sg/wslin/'>Prof. Weisi Lin</a>. I also spent one wonderful year via a joint PhD program in Technische Universität Darmstadt, under the supervision of Dr. Michael Goesele. I hold a B.S. degree from Harbin Institute of Technology.

My research broadly focuses on **3D Vision** and **Generative AI**, with particular interests in visual localization, novel view synthesis, visual text generation and video prediction. **I am recruiting PhD and Mphil students** who want to work on research topics such as image/video generation/editting, feature matching and gaussian splatting. If you are interested in joining my group, please email me with your CV to **wentaocheng(AT)uic.edu.cn.**

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.02*: I will join **UIC** as an Associate Professor.
- *2024.08*: One paper accepted by IEEE Signal Processing Letters. 
- *2024.02*: One paper accepted by **CVPR** 2024.
- *2024.01*: I receive the support from NSFC (Youth Program).

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<code class="language-plaintext highlighter-rouge">Arxiv</code> <a href="https://arxiv.org/pdf/2501.05892">Beyond Flat Text: Dual Self-inherited Guidance for Visual Text Generation</a>, Minxing Luo, Zixun Xia, Liaojun Chen, Zhenhang Li, Weichao Zeng, Jianye Wang, <strong>Wentao Cheng</strong>, Yaxing Wang, Yu Zhou, Jian Yang

<code class="language-plaintext highlighter-rouge">SPL 2024</code> 
<code class="language-plaintext highlighter-temp">CCF-C</code>
<a href="https://ieeexplore.ieee.org/abstract/document/10705059">MVP: One-Shot Object Pose Estimation by Matching With Visible Points</a>, <strong>Wentao Cheng</strong>, Minxing Luo | <a href="https://github.com/wtchengcv/MVP"><strong>Code</strong>

<code class="language-plaintext highlighter-rouge">CVPR 2024</code> 
<code class="language-plaintext highlighter-temp">CCF-A</code>
<a href="https://zzcheng.top/assets/pdf/2024_CVPR_ExtDM.pdf">ExtDM: Distribution Extrapolation Diffusion Model for Video Prediction</a>, Zhicheng Zhang, Junyao Hu, <strong>Wentao Cheng</strong>, Danda Paudel, Jufeng Yang | <a href="https://zzcheng.top/ExtDM"><strong>Project</strong></a> | <a href="https://github.com/nku-zhichengzhang/ExtDM"><strong>Code</strong>

<code class="language-plaintext highlighter-rouge">Arxiv</code> <a href="https://arxiv.org/pdf/2401.06442">RotationDrag: Point-based Image Editing with Rotated Diffusion Features</a>, Minxing Luo, <strong>Wentao Cheng</strong>, Jian Yang | <a href="https://github.com/Tony-Lowe/RotationDrag"><strong>Code</strong>
</a>

<code class="language-plaintext highlighter-rouge">ICRA 2021</code>
<code class="language-plaintext highlighter-temp">CCF-B</code> <a href="https://arxiv.org/pdf/2108.05047.pdf">Road mapping and localization using sparse semantic visual features</a>, <strong>Wentao Cheng* </strong>, Sheng Yang*, Maomin Zhou, Ziyuan Liu, Yiming Chen, Mingyang Li

<code class="language-plaintext highlighter-rouge">ICCV 2019</code>
<code class="language-plaintext highlighter-temp">CCF-A</code> <a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Cheng_Cascaded_Parallel_Filtering_for_Memory-Efficient_Image-Based_Localization_ICCV_2019_paper.pdf">Cascaded parallel filtering for memory-efficient image-based localization</a>, <strong>Wentao Cheng</strong>, Weisi Lin, Kan Chen, Xinfeng Zhang

<code class="language-plaintext highlighter-rouge">TIP  2019</code>
<code class="language-plaintext highlighter-temp">CCF-A</code> <a href="https://ieeexplore.ieee.org/abstract/document/8704253/">A two-stage outlier filtering framework for city-scale localization using 3D SfM point clouds
</a>, <strong>Wentao Cheng</strong>, Kan Chen, Weisi Lin, Michael Goesele, Xinfeng Zhang, Yabin Zhang

<code class="language-plaintext highlighter-rouge">TIP  2017</code>
<code class="language-plaintext highlighter-temp">CCF-A</code> <a href="https://ieeexplore.ieee.org/abstract/document/8063430/">Multiple-level feature-based measure for retargeted image quality</a>, Yabin Zhang, Weisi Lin, Qiaohong Li, <strong>Wentao Cheng</strong>, Xinfeng Zhang

<code class="language-plaintext highlighter-rouge">TIP  2016</code>
<code class="language-plaintext highlighter-temp">CCF-A</code> <a href="https://ieeexplore.ieee.org/abstract/document/7725940/">A data-driven point cloud simplification framework for city-scale image-based localization</a>, <strong>Wentao Cheng</strong>, Weisi Lin, Xinfeng Zhang, Michael Goesele, Ming-Ting Sun


<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 💼 Professional Service  
- **Reviewer for Conferences**: CVPR 2023-2025, ICCV 2023, ICRA 2023, ICIP 2021-2024, PRCV 2023, ICASSP 2021-2023.
- **Reviewer for Journals**: IEEE Transaction on Robotics, IEEE Transaction on Image Processing, IEEE Transaction on Multimedia, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Signal Processing Letters, IEEE Robotics and Automation Letters, Journal of Visual Communication and Image Representation.

# <i class="fas fa-book"></i> Teaching
- Data Structures, 2024 Fall, Nankai University.



# 📖 Educations
- Joint-PhD, Nanyang Technological University, Singapore. 
- Joint-PhD, Technische Universität Darmstadt, Germany. 
- Bachelor, Harbin Institute of Technology, China.

