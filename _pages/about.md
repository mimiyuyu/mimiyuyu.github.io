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

I'm a third year graduate student at College of Biomedical Engineering, [Sichuan University](https://www.scu.edu.cn/), advised by Prof. Jing Zhang. I got my bachelor’s degree in Medical Information Engineering in 2022. I’m now working with Dr. Xiyue Wang (Stanford) and Sen Yang (Tencent) on histopathology image guided clinical tasks. Previously, I focused on the study of ct-guided surgical path planning system for lung puncture. 

My research interest includes Computational Pathology and Biomedical Image Processing.

I am deeply indebted to everyone who has supported me in my academic career.



# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Our work about pathology foundation model has been accepted by **Nature**!
- *2023.02*: &nbsp;🎉🎉 One paper accepted by Physics in Medicine & Biology. 
- *2022.06*: &nbsp;🎉🎉 I graduated from Sichuan University with a bachelor's degree. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">nature</div><img src='images/paper1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A pathology foundation model for cancer diagnosis and prognosis prediction](https://www.nature.com/articles/s41586-024-07894-z)

Xiyue Wang†, Junhan Zhao†, Eliana Marostica, Wei Yuan, Jietian Jin, **Jiayu Zhang**, Ruijiang Li, Hongping Tang, Kanran Wang, Yu Li, Fang Wang, Yulong Peng, Junyou Zhu, Jing Zhang, Christopher R. Jackson, Jun Zhang, Deborah Dillon, Nancy U. Lin, Lynette Sholl, Thomas Denize, David Meredith, Keith L. Ligon, Sabina Signoretti, Shuji Ogino, Jeffrey A. Golden, MacLean P. Nasrallah, Xiao Han, Sen Yang#, Kun-Hsing Yu#
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Physics in Medicine & Biology</div><img src='images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Path planning algorithm for percutaneous puncture
lung mass biopsy procedure based on the multi-objective constraints and fuzzy optimization](https://iopscience.iop.org/article/10.1088/1361-6560/ad2c9f)

**Jiayu Zhang†**, Jing Zhang, Ping Han, Xinzu Chen, Yu Zhang, Wen Li, Jing Qin and Ling He#


- In this work, we proposed a multi-constrained objective optimization model based on clinical criteria for the percutaneous puncture lung mass biopsy procedure. Based on fuzzy optimization, a multidimensional spatial Pareto front algorithm has been developed for optimal path selection. The algorithm finds optimal paths, which are displayed on 3D images, and provides reference points for clinicians’surgical path planning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCISP 2023</div><img src='images/paper3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Virtual Surgery System for Lung Biopsy](https://ieeexplore.ieee.org/abstract/document/10355809)

Jianquan Zhong†, Fulian Zhong, Ling Tang, **Jiayu Zhang**, Hao Feng, Jiran Deng, He Ling and Jing Zhang#


- In this work, we designed an advanced preoperative rehearsal system for lung puncture biopsy surger, which enables the creation of threedimensional model of both the lung and the puncture needle. It mechanically models the skin, fat and muscle of the chest wall to establish a virtual surgical rehearsal environment combined with force feedback technology, leads to high degree of effectiveness and clinical value that can serve as an auxiliary tool in lung puncture surgery. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCISP 2022</div><img src='images/paper4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CT-guided automatic path planning for lung puncture](https://ieeexplore.ieee.org/document/9974252)

Jianquan Zhong†, Jinyang Shen, Ling Tang, Ruizhi Hao, **Jiayu Zhang**, Yuhang Gong, Jing Zhang#


- An automatic CT image-based path planning method for lung puncture surgery is proposed due to high failure rate, time consumption, and the high radiation dose of the existing percutaneous lung puncture surgery. In this work, we implemented automatic organ segmentation of chest CT images and defined six constraining conditions combined with clinical a priori knowledge to find the optimal puncture path using a multi-objective Pareto optimization method. 
</div>
</div>

# 🎖 Honors and Awards
- *2024.02*  **Excellent Paper Award** in 2023 by the **A**sia **P**acific **I**nstitute of **S**cience and **E**ngineering (APISE). 
- *2023.11*  **Excellent Oral Presentation Award** in CCISP 2023.
- *2022.11*  **Best Paper Award** in International **C**onference on **C**ommunication, **I**mage and **S**ignal **P**rocessing (CCISP). 

# 📖 Educations
- <img src='images/scu.png' alt="sym" width="5%"> *2022.09 - now*, M.Sc. in Biomedical Engineering, Sichuan University. 
- <img src='images/scu.png' alt="sym" width="5%"> *2018.09 - 2022.06*, B.Eng. in Medical Information Engineering, Sichuan University. 

# 💬 Talks
- *2023,11*, “A Virtual Surgery System for Lung Biopsy”, contributed talk at CCISP 2023. (Chengdu, China)
- *2022.11*, “CT-guided automatic path planning for lung puncture”, contributed talk at CCISP 2022. (Chengdu, China)

