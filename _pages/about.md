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

🤔 My research interests include Embodied AI and Generative AI.

🙋‍♂️ If you are seeking any form of <strong>academic cooperation</strong>, please feel free to email me at <a href="hyubq@connect.ust.hk">hyubq@connect.ust.hk</a>.

🎓 I graduated from <strong>Nanjing University with a B.S. degree in Electronic Science and Engineering</strong>.
I had an internship at the <strong>CITE LAB, Nanjing University</strong>, supervised by Prof. <strong><a href="https://scholar.google.com/citations?user=8hZIngIAAAAJ&amp;hl=en">Xun Cao</a></strong> and Prof. <strong><a href="https://cite.nju.edu.cn/People/Faculty/20220722/i226168.html">Shen Qiu</a></strong>

# Industry Experience
<div style="display: flex; align-items: center; gap: 2rem; flex-wrap: wrap; margin: 1rem 0 2rem;">
  <div style="display: flex; align-items: center; flex-shrink: 0; width: 240px; aspect-ratio: 16 / 9; padding: 18px; box-sizing: border-box; overflow: hidden; background: #050505; border: 1px solid #d9d9d9; border-radius: 8px; box-shadow: 0 4px 12px rgba(0, 0, 0, .14);">
    <img src="images/tencent_x.png" alt="Tencent Robotics X" style="display: block; width: 100%; height: auto;">
  </div>
  <div style="flex: 1; min-width: 280px;">
    <p style="display: flex; justify-content: space-between; gap: 1rem; flex-wrap: wrap; margin-bottom: .5rem;">
      <strong>Tencent Robotics X, Shenzhen, China</strong>
      <em>2025.08 - Present</em>
    </p>
    <ul style="margin: 0;">
      <li>Project: VLA/WAM Pretraining for Robot Manipulation</li>
      <li>Worked with Dr. <a href="https://hetolin.github.io/">Haitao Lin</a></li>
    </ul>
  </div>
</div>

# News
- *2026.06*: &nbsp; 🎉 Our paper is accepted by RSS 2026!
- *2024.06*: &nbsp; 🎉 I was awarded as Outstanding Graduate of Nanjing Universtiy.
- *2024.04*: &nbsp; 🎉 HKPFS get!
- *2023.12*: &nbsp; 🎉 We won the Gold prize in National College Students Innovation and Entrepreneurship Competition!
- *2023.9*: &nbsp; 🎉 Our paper is accepted by ACM MM!
- *2022.8*: &nbsp; 🎉 We won the First prize of National College students Electronic Design Competition! 
 

# Publications
<!-- GeniWorld -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src="https://chenghaogu.github.io/GeniWorld/assets/figures/figure1.webp" alt="GeniWorld" width="100%">
    </div>
  </div>
<div class="paper-box-text">

<h1 style="font-weight: bold">
  <a href="https://chenghaogu.github.io/GeniWorld/" target="_blank">
    GeniWorld: A Generalizable Interactive World Model for Robotic Manipulation via Visual Actions
  </a>
</h1>

<p>
  <a href="https://chenghaogu.github.io/">Chenghao Gu*</a>,
  <strong><a href="https://hanyangyu1021.github.io/"><font color="#fc8803">Hanyang Yu*</font></a></strong>,
  <a href="https://eckertzhang.github.io/">Jingbo Zhang</a>,
  <a href="https://hetolin.github.io/">Haitao Lin</a>,
  <a href="https://zhangwenyao1.github.io/">Wenyao Zhang</a>,
  Jinghe Wang,
  Hanglei Jin,
  Shuzhao Xie,
  Jingyan Jiang,
  Zhi Wang
</p>

  <p style="display: flex; flex-wrap: wrap; align-items: center; gap: 6px;">
    <a href="https://chenghaogu.github.io/GeniWorld/">
      <img src="https://img.shields.io/badge/Project-Page-4C8BF5?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page" />
    </a>
    <a href="https://arxiv.org/abs/2608.06332">
      <img src="https://img.shields.io/badge/arXiv-2608.06332-b31b1b.svg?style=flat-square" alt="arXiv" />
    </a>
  </p>

  - GeniWorld converts robot actions into visual actions for controllable world modeling, enabling closed-loop interaction, robust generalization to unseen environments, and improved downstream policies.
  </div>
</div>


<!-- MaskWAM -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <video autoplay muted loop playsinline preload="metadata" width="100%"
             poster="https://hanyangyu1021.github.io/maskwam.github.io/static/images/teaser.png"
             style="aspect-ratio: 16 / 9; object-fit: cover; background: #f1f5f9;"
             onloadedmetadata="this.playbackRate = 4;">
        <source src="https://hanyangyu1021.github.io/maskwam.github.io/static/videos/pink.mp4" type="video/mp4">
        Your browser does not support embedded videos.
      </video>
    </div>
  </div>
<div class="paper-box-text">

<h1 style="font-weight: bold">
  <a href="https://hanyangyu1021.github.io/maskwam.github.io/" target="_blank">
    MaskWAM: Unifying Mask Prompting and Prediction for World-Action Models
  </a>
</h1>

<p>
  <strong><a href="https://hanyangyu1021.github.io/"><font color="#fc8803">Hanyang Yu</font></a></strong>,
  <a href="https://hetolin.github.io/">Haitao Lin</a>,
  <a href="https://eckertzhang.github.io/">Jingbo Zhang</a>,
  <a href="https://zhangwenyao1.github.io/">Wenyao Zhang</a>,
  <a href="https://chenghaogu.github.io/">Chenghao Gu</a>,
  <a href="https://hengli.me/">Heng Li</a>,
  <a href="https://ece.hkust.edu.hk/pingtan">Ping Tan</a>
</p>

  <p style="display: flex; flex-wrap: wrap; align-items: center; gap: 6px;">
    <a href="https://hanyangyu1021.github.io/maskwam.github.io/">
      <img src="https://img.shields.io/badge/Project-Page-4C8BF5?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page" />
    </a>
    <a href="https://github.com/hanyangyu1021/maskwam">
      <img src="https://img.shields.io/github/stars/hanyangyu1021/maskwam?label=stars&amp;logo=github&amp;color=brightgreen&amp;style=flat-square" alt="GitHub Repo Stars" />
    </a>
    <a href="https://www.xiaohongshu.com/explore/6a2ba4ec0000000035024ae6?xsec_token=ABT3qqq3dv9hnxXmebubNi6eyf98ewerr1_QbMdS8iUns=&amp;xsec_source=pc_user" title="小红书">
      <span style="display: inline-flex; width: 32px; height: 20px; align-items: center; justify-content: center; background: #FF2442; border-radius: 3px; vertical-align: middle;">
        <img src="https://cdn.simpleicons.org/xiaohongshu/FFFFFF" alt="小红书" style="height: 14px;" />
      </span>
    </a>
    <a href="https://arxiv.org/abs/2606.13515">
      <img src="https://img.shields.io/badge/arXiv-2606.13515-b31b1b.svg?style=flat-square" alt="arXiv" />
    </a>
  </p>

  - We introduce MaskWAM, an object-centric world-action model that uses masks as both visual prompts and prediction targets to improve spatial grounding, robustness, and policy generalization.
  </div>
</div>


<!-- Pose-VLA -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">RSS 2026 · Oral Presentation</div>
      <img src='images/posevla.jpg' alt="PoseVLA" width="100%" style="aspect-ratio: 5 / 3; object-fit: cover;">
    </div>
  </div>
<div class="paper-box-text">
  
<h1 style="font-weight: bold">
  <a href="https://hetolin.github.io/PoseVLA/" target="_blank">
    PoseVLA: Universal Pose Pretraining for Generalizable Vision-Language-Action Policies
  </a>
</h1>

<p>
  <a href="https://hetolin.github.io/">Haitao Lin*</a>, 
  <strong><font color="#fc8803">Hanyang Yu*</font></strong>, 
  <a href="#">Jingshun Huang*</a>, 
  <a href="https://cghezhang.github.io/">He Zhang</a>, 
  <a href="https://ygling2008.github.io/">Yonggen Ling</a>, 
  <a href="https://pingtan.people.ust.hk/index.html">Ping Tan</a>, 
  <a href="https://scholar.google.com/citations?user=DTbhX6oAAAAJ&hl=en">Xiangyang Xue</a>, 
  <a href="http://yanweifu.github.io/">Yanwei Fu</a>
</p>

  <p style="display: flex; flex-wrap: wrap; align-items: center; gap: 6px;">
    <a href="https://hetolin.github.io/PoseVLA/">
      <img src="https://img.shields.io/badge/Project-Page-4C8BF5?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page" />
    </a>
    <a href="https://github.com/hetolin/PoseVLA">
      <img src="https://img.shields.io/github/stars/hetolin/PoseVLA?label=stars&amp;logo=github&amp;color=brightgreen&amp;style=flat-square" alt="GitHub Repo Stars" />
    </a>
    <a href="https://www.xiaohongshu.com/explore/6a4c8368000000001702bf58?xsec_token=ABviBX5mPNOUyhgfB2GV6DPReMOuZ3LI3iIgxzTMtLxPk=&amp;xsec_source=pc_user" title="小红书">
      <span style="display: inline-flex; width: 32px; height: 20px; align-items: center; justify-content: center; background: #FF2442; border-radius: 3px; vertical-align: middle;">
        <img src="https://cdn.simpleicons.org/xiaohongshu/FFFFFF" alt="小红书" style="height: 14px;" />
      </span>
    </a>
    <a href="https://arxiv.org/html/2602.19710v1">
      <img src="https://img.shields.io/badge/arXiv-2602.19710-b31b1b.svg?style=flat-square" alt="arXiv" />
    </a>
  </p>

  - PoseVLA decouples VLA training into universal pose pretraining and embodiment-specific post-training, learning transferable 3D spatial priors for efficient robot policy adaptation.
  </div>
</div>


<!-- LM-Gaussian -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv 2024</div>
      <img src='images/lmgaussian.png' alt="WormTrack" width="100%">
    </div>
  </div>
<div class="paper-box-text">
  
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

  <p style="display: flex; flex-wrap: wrap; align-items: center; gap: 6px;">
    <a href="https://hanyangyu1021.github.io/lm-gaussian.github.io/">
      <img src="https://img.shields.io/badge/Project-Page-4C8BF5?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page" />
    </a>
    <a href="https://github.com/hanyangyu1021/LMGaussian">
      <img src="https://img.shields.io/github/stars/hanyangyu1021/LMGaussian?label=stars&amp;logo=github&amp;color=brightgreen&amp;style=flat-square" alt="GitHub Repo Stars" />
    </a> 
    <a href="https://arxiv.org/abs/2409.03456">
      <img src="https://img.shields.io/badge/arXiv-2409.03456-b31b1b.svg?style=flat-square" alt="arXiv" />
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
<div class="paper-box-text">
  
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
  <a href="https://scholar.google.com/citations?user=8hZIngIAAAAJ&amp;hl=en">Xun Cao</a>,
</p>

  <p style="display: flex; flex-wrap: wrap; align-items: center; gap: 6px;">
    <a href="https://github.com/Jeerrzy/wormstudio">
      <img src="https://img.shields.io/badge/Project-Page-4C8BF5?style=flat-square&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page" />
    </a>
    <a href="https://github.com/Jeerrzy/wormstudio">
      <img src="https://img.shields.io/github/stars/Jeerrzy/wormstudio?label=stars&amp;logo=github&amp;color=brightgreen&amp;style=flat-square" alt="GitHub Repo Stars" />
    </a> 
  </p>

  - We studies on the challenges and existing solutions for MOT in worm crowds by building a well-designed dataset!
  </div>
</div>



# Selected Honors and Awards
- Outstanding Graduate of Nanjing University, 2024
- National Gold Award, China International College Students' Innovation Competition, 2023
- Provincial First Prize, National College Students Electronic Design Competition, 2022
- Huawei Cup Gold Award (Top One), 2023
- People's Scholarship · Jin Xiao Electronics Scholarship · People's Special Talent Scholarship

# Educations
- *2024.08 - (now)*, PhD, ECE, The Hong Kong University of Science and Technology (HKUST), HongKong.
- *2020.09 - 2024.06*, Undergraduate, School of Electronics Science and Engineering, Nanjing University.
- *2017.09 - 2020.06*, Jiangsu Tianyi High School, WUXI.


