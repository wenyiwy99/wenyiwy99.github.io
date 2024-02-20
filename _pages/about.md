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

Hi, I am Yi Wen. I have been graduated from [School of Mathematicas and Statistics](https://math.csu.edu.cn/), Centre South University (中南大学数学与统计学院) with a bachelor's degree and [Colleage of Computer Science and Technology](https://www.nudt.edu.cn/yssz/jsjxy/index.htm), National University of Defense Technology (国防科技大学计算机学院) with a master's degree, advised by [Professor Xinwang LIU (刘新旺教授)](https://xinwangliu.github.io/). 

**Research Interests**: Graph-based recommedation, multi-view learning, clustering. 


# 🔥 News
- *2023.12*: &nbsp;🎉🎉 One Paper is accepted by AAAI 2024. 
- *2023.09*: &nbsp; One Paper is accepted by TCSVT. 
- *2023.07*: &nbsp; Three Papers are accepted by ACM MM 2023.
- *2023.06*: &nbsp; One Paper is accepted by TNNLS.
- *2023.06*: &nbsp; One Paper is accepted by TKDE.

# 📝 Publications 
(<sup>*</sup> indicates equal contribution;  <sup>#</sup> indicates corresponding authorship.) 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/SIMVC-SA.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size = 3><h5>Scalable Incomplete Multi-View Clustering with Structure Alignment</h5></font>

**Yi Wen**, Siwei Wang<sup>#</sup>, Ke Liang, Weixuan Liang, Xinhang Wan, Xinwang Liu<sup>#</sup>, Suyuan Liu, Jiyuan Liu, En Zhu. [**Code**](https://github.com/wenyiwy99/SIMVC-SA) [**PDF**](https://arxiv.org/pdf/2308.16541.pdf)

- In order to solve the Anchor-Unaligned Problem for Incomplete Data, a novel alignment module is proposed in this paper to capture the view-specific structure. With the guidance of structure information, the cross-view anchor correspondence mapping can be refined adequately.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/EMVGC-LG.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size = 3><h5>Efficient Multi-View Graph Clustering with Local and Global Structure Preservation</h5></font>

**Yi Wen**<sup>*</sup>, Suyuan Liu<sup>*</sup>, Xinhang Wan, Siwei Wang, Ke Liang, Xinwang Liu<sup>#</sup>, Xihong Yang, Pei Zhang. [**Code**](https://github.com/wenyiwy99/EMVGC-LG) [**PDF**](https://arxiv.org/pdf/2309.00024.pdf)

- We design an anchor graph learning framework termed Efficient Multi-View Graph Clustering with Local and Global Structure Preservation (EMVGC-LG). With the proven properties, the proposed anchor graph paradigm can not only capture the global structure between data but also well approximate the local structure.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS</div><img src='images/UPMGC-GM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<font size = 3><h5>Unpaired Multi-View Graph Clustering with Cross-View Structure Matching</h5></font>

**Yi Wen**, Siwei Wang, Qing Liao, Weixuan Liang, Ke Liang, Xinhang Wan, Xinwang Liu<sup>#</sup>.  [**Code**](https://github.com/wenyiwy99/UPMGC-SM) [**PDF**](https://arxiv.org/pdf/2307.03476.pdf)

- We propose a new paradigm for graph-based MVC termed Data-Unpaired Problem (DUP). Our solution to this problem is of great significance and can avoid the strong assumption of the alignment of cross-view data in data collection.
</div>
</div>

- **Sample-level Cross-view Similarity Learning for Incomplete Multi-view Clustering**, Suyuan Liu, Junpu Zhang, **Yi Wen**, Xihong Yang, Siwei Wang, Yi Zhang, En Zhu, Chang Tang, Long Zhao, Xinwang Liu<sup>#</sup>, **AAAI 2024**. [**Code**](https://github.com/Tracesource/SCSL) 

- **How to Construct Corresponding Anchors for Incomplete Multiview Clustering**, Shengju Yu, Siwei Wang, **Yi Wen**, Ziming Wang, Zhigang Luo, En Zhu, Xinwang Liu<sup>#</sup>, **TCSVT**.  [**PDF**]()

- **Knowledge Graph Contrastive Learning based on Relation-Symmetrical Structure**, Ke Liang, Yue Liu, Sihang Zhou, Wenxuan Tu, **Yi Wen**, Xihong Yang, Xiangjun Dong, Xinwang Liu<sup>#</sup>, **TKDE**.  [**PDF**]()
  
- **DealMVC: Dual Contrastive Calibration for Multi-view Clustering**, Xihong Yang, Jiaqi Jin, Siwei Wang, Ke Liang, Yue Liu, **Yi Wen**, Suyuan Liu, Sihang Zhou, Xinwang Liu<sup>#</sup>, En Zhu<sup>#</sup>, **ACM MM 2023**. [**Code**](https://github.com/xihongyang1999/DealMVC) [**PDF**](https://arxiv.org/pdf/2308.09000.pdf)

- **Auto-weighted Multi-view Clustering for Large-scale Data**, Xinhang Wan, Xinwang Liu<sup>#</sup>, Jiyuan Liu, Siwei Wang, **Yi Wen**, Weixuan Liang, En Zhu, Zhe Liu, Lu Zhou, **AAAI 2023**. [**Code**](https://github.com/wanxinhang/AAAI-2023-AWMVC) [**PDF**](https://arxiv.org/pdf/2303.01983.pdf)

- **Continual Multi-view Clustering**, Xinhang Wan, Jiyuan Liu, Weixuan Liang, Xinwang Liu<sup>#</sup>, **Yi Wen**, En Zhu, **ACM MM 2022**. [**Code**](https://github.com/wanxinhang/CMVC) [**PDF**](https://www.researchgate.net/profile/Xinhang-Wan/publication/364478623_Continual_Multi-view_Clustering/links/6386c9486b39e338d42e62a2/Continual-Multi-view-Clustering.pdf)



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
