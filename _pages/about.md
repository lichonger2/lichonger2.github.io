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

Wanmeng Li is currently a second-year Ph.D. student at the [Intelligent Autonomous Systems Laboratory (IAS-Lab)](https://robotics.dei.unipd.it/) at the [University of Padua](https://www.unipd.it/), under the supervision of [Prof. Alberto Pretto](https://albertopretto.altervista.org/) and [Prof. Emanuele Menegatti](https://www.dei.unipd.it/~emg/).

His research interests include data-efficient 3D LiDAR point cloud perception, transfer learning, unsupervised/semi-supervised learning, and image enhancement.

He received his Master’s degree from the [City University of Hong Kong](https://www.cityu.edu.hk/) and his Bachelor’s degree from [Hebei University of Technology](https://eweb.hebut.edu.cn/)


# 🔥 News
- [06/2025] - DPGLA was selected for oral presentation at [IROS 2025](https://www.iros25.org/).

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">IROS 2025</div>
      <img src='images/DPGLA.png' alt="DPGLA" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **DPGLA: Bridging the Gap between Synthetic and Real Data for Unsupervised Domain Adaptation in 3D LiDAR Semantic Segmentation** [[Code]](https://github.com/lichonger2/DPGLA)  
  **Wanmeng Li**, Simone Mosco, Daniel Fusaro, Alberto Pretto  
  *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2025*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECMR 2025</div>
      <img src='images/ECMR.png' alt="ConSamp" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **ConUDA: Confidence-Guided Pseudo-Label Sampling for Unsupervised Domain Adaptation in 3D LiDAR Semantic Segmentation** [[Code]](https://github.com/lichonger2/ConUDA)  
  **Wanmeng Li**, Simone Mosco, Daniel Fusaro, Alberto Pretto  
  *European Conference on Mobile Robots (ECMR), 2025*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SIMPAR 2025</div>
      <img src='images/simpar.png' alt="UnderwaterPlaceRecognition" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **Real-time Underwater Place Recognition in Synthetic and Real Environments using Multibeam Sonar and Learning-based Descriptors**  
  Daniel Fusaro, Simone Mosco, **Wanmeng Li**, Alberto Pretto  
  *IEEE International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR), 2025*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CIS-RAM 2024</div>
      <img src='images/CIS_RAM.png' alt="UnderwaterPlaceRecognition" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **P-SVM2: Enhancing LiDAR-based Traversability Analysis with Augmented Point Cloud Descriptor for Autonomous Mobile Systems** [[Code]](https://github.com/lichonger2/P-SVM2_TraversabilityAnalysis)  
  **Wanmeng Li**, Daniel Fusaro, Emilio Olivastri, Alberto Pretto  
  *IEEE International Conference on Cybernetics and Intelligent Systems (CIS) and IEEE International Conference on Robotics, Automation and Mechatronics (RAM), 2025*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICRA 2024</div>
      <img src='images/ICRA2024.png' alt="SonarAUVPositioning" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **A Sonar-based AUV Positioning System for Underwater Environments with Low Infrastructure Density**  
  Emilio Olivastri, Daniel Fusaro, **Wanmeng Li**, Simone Mosco, Alberto Pretto  
  *IEEE International Conference on Robotics and Automation (ICRA) Workshop, 2024*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICVS 2023</div>
      <img src='images/ICVS2023.png' alt="SonarDescriptorGeneralization" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **Improving Generalization of Synthetically Trained Sonar Image Descriptors for Underwater Place Recognition** [[Code]](https://github.com/ivano-donadi/sdpr)  
  Ivano Donadi, Emilio Olivastri, Daniel Fusaro, **Wanmeng Li**, Daniele Evangelista, Alberto Pretto  
  *International Conference on Computer Vision Systems (ICVS), 2023*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICWAPR 2023</div>
      <img src='images/ICWAPR.png' alt="LowLightEnhancement" width="90%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">
  **Unsupervised Low-Light Image Enhancement Based on Deep Lightness and Grey Pixel Estimation**  
  Houwang Zhang, **Wanmeng Li**, Leanne Lai-Hang Chan  
  *International Conference on Wavelet Analysis and Pattern Recognition (ICWAPR), 2023*  
  <strong><span class='show_paper_citations' data='YOUR_SCHOLAR_ID_HERE'></span></strong>
  </div>
</div>



# 🎖 Honors and Awards
- A nice person
- *2020.12* Graduated with Distinction from the City University of Hong Kong.

# 📖 Educations
- *2023.10 – now*, Ph.D. student in Information Engineering, University of Padua, Italy  
- *2019.09 – 2020.12*, M.Sc. in Multimedia Information Technology, City University of Hong Kong, Hong Kong, China  
- *2015.09 – 2019.06*, B.Eng. in Communication Engineering, Hebei University of Technology, Tianjin, China

# 💻 Working Experience
- *2023.03 – 2023.09*, Research Fellow, University of Padua, Italy  
- *2022.02 – 2023.02*, Research Assistant, City University of Hong Kong, Hong Kong, China  
- *2020.12 – 2022.01*, Product Manager, Hangzhou Hikvision Digital Technology Co., Ltd., Hangzhou, China
- *2019.10 – 2019.12*, Video Development Engineer Intern, ZTE Corporation, Shenzhen, China

