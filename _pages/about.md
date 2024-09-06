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

👋 I'm currently a Phd Candidate of Hong Kong University of Science and Technology(HKUST), supervised by Prof. <strong><a href="https://scholar.google.com/citations?user=XhyKVFMAAAAJ&hl=en">Ping Tan</a></strong>

🤔 My research interests include 3D reconstruction and 3D AIGC. My google scholar is here <a href='https://scholar.google.com/citations?user=SCHOLAR_ID&user=rsnb8vMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

🙋‍♂️ If you are seeking any form of <strong>academic cooperation</strong>, please feel free to email me at <a href="hanyangyu1021@gmail.com">Hanyangyu1021 AT gmail DOT com</a>.</p>

🎓 I graduated from <strong>Nanjing University with a B.S. degree in Electronic Science and Engineering</strong>.
I had an internship at the <strong>CITE LAB, Nanjing University</strong>, supervised by Prof. <strong><a href="https://scholar.google.com/citations?hl=en&amp;user=9z7GPxIAAAAJ">Xun Cao</a></strong> and Prof. <strong><a href="https://cite.nju.edu.cn/People/Faculty/20220722/i226168.html">Shen Qiu</a></strong>

# 🔥 News
- *2024.06*: &nbsp; 🎉 I was awarded as Outstanding Graduate of Nanjing Universtiy.
- *2024.04*: &nbsp; 🎉 HKPFS get!
- *2023.12*: &nbsp; 🎉 We won the Gold prize in National College Students Innovation and Entrepreneurship Competition!
- *2023.9*: &nbsp; 🎉 Our paper is accepted by ACM MM!
- *2022.8*: &nbsp; 🎉 We won the First prize of National College students Electronic Design Competition! 
 

# 📝 Publications 
<!-- LM-Gaussian -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2024</div>
      <img src='images/lmgaussian.png' alt="WormTrack" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1"
  
  <h1 style="font-weight: bold">
  <a href="https://hanyangyu1021.github.io/lm-gaussian.github.io/" target="_blank">
    <span class="gradient-text-1">LM-Gaussian</span>:
      Boost Sparse-view 3D Gaussian Splatting with Large Model Priors
  </a>
</h1>

<p>
  <strong><font color="#fc8803">Hanyang Yu</font></strong>, 
<a href="https://www.xxlong.site/">Xiaoxiao Long†</a>, 
<a href="https://ece.hkust.edu.hk/pingtan">Ping Tan</a>
</p>

  <p>
    <a href="https://hanyangyu1021.github.io/lm-gaussian.github.io/">[🗂️Project Page]</a> 
    <a href="https://github.com/hanyangyu1021/LMGaussian">
      <img src="https://img.shields.io/github/stars/hanyangyu1021/LMGaussian?label=stars&amp;logo=github&amp;color=brightgreen" alt="GitHub Repo Stars" />
    </a> 
    <a href="https://arxiv.org/abs/2409.03456"><img src="https://img.shields.io/badge/arXiv-2404.04363-b31b1b.svg?style=flat-square" alt="arXiv" />
    </a>
  </p>

  - We aim to address sparse-view reconstruction of a 3D scene by leveraging priors from large-scale vision models. 
  </div>
</div>

<!-- WormTrack ACM2023 -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACM 2023</div>
      <img src='images/wormtrack.png' alt="WormTrack" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">
  
  <h1 style="font-weight: bold">
  <a href="https://dl.acm.org/doi/10.1145/3581783.3613812" target="_blank">
    <span class="gradient-text-1">WormTrack</span>:
      Dataset and Benchmark for Multi-Object Tracking in Worm Crowds
  </a>
</h1>
 
<p>
  <a href="https://openreview.net/profile?id=~Zhiyu_Jin3">Zhiyu Jin</a>, 
  <strong><font color="#fc8803">Hanyang Yu</font></strong>, 
  <a href="https://openreview.net/profile?id=~Chengcheng_Huo1">Chen Haul</a>, 
  <a href="https://openreview.net/profile?id=~Linxiang_Wang1">Linxiang Wang</a>,
  <a href="https://openreview.net/profile?id=~Qiu_Shen1">Qiu Shen</a>, 
  <a href="https://scholar.google.com/citations?hl=en&amp;user=9z7GPxIAAAAJ">Xun Cao</a>,
</p>

  <p>
    <a href="https://github.com/Jeerrzy/wormstudio">[🗂️Project Page]</a> 
    <a href="https://github.com/Jeerrzy/wormstudio">
      <img src="https://img.shields.io/github/stars/yisuanwang/Ultraman?label=stars&amp;logo=github&amp;color=brightgreen" alt="GitHub Repo Stars" />
    </a> 
  </p>

  - We studies on the challenges and existing solutions for MOT in worm crowds by building a well-designed dataset!
  </div>
</div>



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2024.08 - (now)*, PhD, ECE, The Hong Kong University of Science and Technology (HKUST), HongKong.
- *2020.09 - 2024.06*, Undergraduate, School of Electronics Science and Engineering, Nanjing University.
- *2017.09 - 2020.06*, Jiangsu Tianyi High School, WUXI.


# 💻 Internships
- *2023.08 - 2023.09*, LightILLUSION, Beijing, China.
