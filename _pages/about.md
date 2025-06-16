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

Hi, I'm Jinhong Wang, a fourth-year Ph.D student studying **Computer Science and Technology** at Zhejiang University, supervised by [Prof. Jian Wu (吴健)](https://person.zju.edu.cn/0004274). I am committed to the unified modeling of multimodal visual scoring (rating) in different fields and with different data. Including but not limited to image quality assessment, aesthetic assessment, disease classification, facial age estimation, composition scoring, satisfaction assessment, monocular depth estimation, etc., the construction of general models for achieving such tasks. Specifically, my research focuses include: 

- Multimodal Large Language Models (MLLMs)
- Multimodel Data Alignment and Fusion
- Ordinal Regression and Spatial Intelligence


I am also interested **Medical Image Analysis**, **Computer Vision**, and **Generative Models**. I have published nearly 20 papers at the top international AI conferences.

 <!-- with total <a href='https://scholar.google.com/citations?user=gyU139cAAAAJ'>google scholar citations </a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=gyU139cAAAAJ'><strong><span id='total_cit'></span></strong><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations

<div style="display: flex; align-items: center;"><img src='images/zju.jpg' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>2021.09 - Present</i>, Ph.D Student: Computer Science and Technology, <a href="https://www.zju.edu.cn/">Zhejiang University</a>, Hangzhou, China</li>
	</ul>
</div>

<div style="display: flex; align-items: center;"><img src='images/zjut.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>2017.09 - 2021.06</i>, Undergraduate Student: Network Enginering, <a href="https://www.zjut.edu.cn/">Zhejiang University of Technology</a>, Hangzhou, China</li>
	</ul>
</div>

# 💻 Internships

<div style="display: flex; align-items: center;"><img src='images/mayi.jpeg' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>2024.03 - Present</i>, Research Intern: Multi-model Large Language Models on AIGC, <a href="https://www.antgroup.com/">Ant Group</a>, Hangzhou, China</li>
	</ul>
</div>

<div style="display: flex; align-items: center;"><img src='images/baidu.jpeg' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>2021.06 - 2021.10</i>, Research Intern: AI for interpersonal relationship and job recommendation, Baidu Talent Intelligence Center (TIC) of <a href="https://www.zjut.edu.cn/">Baidu Inc.</a>, Beijing, China</li>
	</ul>
</div>

# 📝 Publications 

## 🔢 MLLMs, Visual Rating/Ordinal Regression

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/iccv2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ord2Seq: Regarding Ordinal Regression as Label Sequence Prediction](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Ord2Seq_Regarding_Ordinal_Regression_as_Label_Sequence_Prediction_ICCV_2023_paper.html)

**Jinhong Wang**, Yi Cheng, Jintai Chen, TingTing Chen, Danny Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/Ord2Seq) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:zYLM7Y9cAGgC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:zYLM7Y9cAGgC'></span></strong> 

![](https://img.shields.io/badge/Ordinal Regression-224B8D) ![](https://img.shields.io/badge/Visual Rating-224B8D) 

</div>
</div>


- `IJCAI 2025` <span style="color:red">(Oral)</span> [Dual-level Fuzzy Learning with Patch Guidance for Image Ordinal Regression](https://arxiv.org/pdf/2505.05834), Chunlai Dong, Haochao Ying, Qibo Qiu, **Jinhong Wang**, et al.

- `IJCAI 2023` <span style="color:red">(Oral)</span> [Robust image ordinal regression with controllable image generation](https://arxiv.org/pdf/2305.04213), Yi Cheng, Haochao Ying, Renjun Hu, **Jinhong Wang**, et al.

## 👀 Computer Vision, Spatial Intelligence

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scalable Autoregressive Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Scalable_Autoregressive_Monocular_Depth_Estimation_CVPR_2025_paper.html)

**Jinhong Wang**, Jian Liu, Dongqi Tang, Weiqiang Wang, Wentong Li, Danny Chen, Jintai Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/DAR) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:LkGwnXOMwfcC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:LkGwnXOMwfcC'></span></strong> 

![](https://img.shields.io/badge/Monocular Depth Estimation-224B8D) 
</div>
</div>

- ``WACV 2025`` [Position: Prospective of Autonomous Driving-Multimodal LLMs World Models Embodied Intelligence AI Alignment and Mamba](https://openaccess.thecvf.com/content/WACV2025W/LLVMAD/html/Ma_Position_Prospective_of_Autonomous_Driving_-_Multimodal_LLMs_World_Models_WACVW_2025_paper.html), Yunsheng Ma, Wenqian Ye, Can Cui, Haiming Zhang, Shuo Xing, Fucai Ke, **Jinhong Wang**, et al.




## 🏥 Medical AI, Multi-modal Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/lkm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LKM-UNet: Large Kernel Vision Mamba UNet for Medical Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_34)

**Jinhong Wang**, Jintai Chen, Danny Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/LKM-UNet) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:ufrVoPGSRksC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:ufrVoPGSRksC'></span></strong> 

![](https://img.shields.io/badge/Medical Image Segmentation-224B8D) ![](https://img.shields.io/badge/Mamba-224B8D) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMI 2023 (IF:10.6)</div><img src='images/tmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Transformer-Based Knowledge Distillation Network for Cortical Cataract Grading](https://ieeexplore.ieee.org/abstract/document/10294274)

**Jinhong Wang**, Zhe Xu, Wenhao Zheng, Haochao Ying, Tingting Chen, Zuozhu Liu, Danny Z Chen, Ke Yao, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/LKM-UNet) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:ufrVoPGSRksC'></span></strong> 

![](https://img.shields.io/badge/Medical Image Grading-224B8D) ![](https://img.shields.io/badge/Multi modal Learning-224B8D)  ![](https://img.shields.io/badge/Distillation Learning-224B8D) 

</div>
</div>


- `BIBM 2024` <span style="color:red">(Oral)</span> [Multi-rater Prompting for Ambiguous Medical Image Segmentation](https://ieeexplore.ieee.org/abstract/document/10822080), **Jinhong Wang**, Yi Cheng, Jintai Chen, et al.

- `BIBM 2022` [CTT-Net: a multi-view cross-token transformer for cataract postoperative visual acuity prediction](https://ieeexplore.ieee.org/abstract/document/9995392), **Jinhong Wang**, Jingwen Wang, Tingting Chen, et al.

- `Neural Computing and Applications 2023 (IF:4.5)` [D-former: A u-shaped dilated transformer for 3d medical image segmentation](https://link.springer.com/article/10.1007/s00521-022-07859-1), Yixuan Wu, Kuanlun Liao, Jintai Chen, **Jinhong Wang**, et al.

- `JBHI 2023 (IF:7.1)` [Polygonal Approximation Learning for Convex Object Segmentation in Biomedical Images with Bounding Box Supervision](https://ieeexplore.ieee.org/abstract/document/10354298), Wenhao Zheng, Jintai Chen, Kai Zhang, Jiahuan Yan, **Jinhong Wang**, et al.

- `Fronties in Medicne 2023 (IF:3.1)` [Prediction of postoperative visual acuity in patients with age-related cataracts using macular optical coherence tomography-based deep learning method](https://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2023.1165135/full), Jingwen Wang, **Jinhong Wang**, Dan Chen, et al.

- `MICCAI 2022` [Automating blastocyst formation and quality prediction in time-lapse imaging with adaptive key frame selection](https://link.springer.com/chapter/10.1007/978-3-031-16440-8_43), Tingting Chen, Yi Cheng, **Jinhong Wang**, et al.

# 🎖 Honors and Awards

## 🆚 ACM Competition

<div style="display: flex; align-items: center;"><img src='images/acm1.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>🥈 Silver Medal 银奖</i> - 2019 ICPC Asia-East Continent Final (国际大学生程序设计竞赛亚洲区域总决赛) </li>
	</ul>
</div>


<div style="display: flex; align-items: center;"><img src='images/acm2.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>🥈 Silver Medal 银奖</i> - 2019 ICPC Asia Region Contest, Xuzhou(国际大学生程序设计竞赛亚洲区域赛徐州站) </li>
	</ul>
</div>

<div style="display: flex; align-items: center;"><img src='images/acm3.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>🥈 Silver Medal 银奖</i> - 2019 ICPC Asia Region Contest, Nanchang(国际大学生程序设计竞赛亚洲区域赛南昌站) </li>
	</ul>
</div>




<div style="display: flex; align-items: center;"><img src='images/CCPC2.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>🥈 Silver Medal 银奖</i> - 2019 China Collegiate Programming Contest, Harbin(中国大学生程序设计竞赛哈尔滨站) </li>
	</ul>
</div>

<div style="display: flex; align-items: center;"><img src='images/CCPC.png' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i>🥈 Silver Medal 银奖</i> - 2019 China Collegiate Programming Contest, National Invitational Contest, Hunan (中国大学生程序设计竞赛全国邀请赛湖南) </li>
	</ul>
</div>


## 🤖 AI/Software Competition

<div style="display: flex; align-items: center;"><img src='images/spark.jpg' width="8%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i> 🥉 季军 </i> - 2020 <a href="https://tianchi.aliyun.com/competition/entrance/531796/rankingList">Spark-天池数字人体AI脊柱疾病智能诊断大赛</a> (4/3108) </li>
	</ul>
</div>



<div style="display: flex; align-items: center;"><img src='images/huawei.jpg' width="20%" style="margin: 15px 10px 15px 10px;">
	<ul style="margin-top: 15px;">
		<li><i> TOP 64 (64强) </i> - 2020华为软件精英挑战赛, 杭厦赛区 </li>
	</ul>
</div>


## 🏫 School Scholarship

- *2024.12* Huawei Elite Scholarship (1%)
- *2024.12* School First-class Scholarship (5%)
- *2023.12* School First-class Scholarship (5%)
- *2022.12* School Second-class Scholarship (10%)
- *2019.12* Province Scholarship (2%)
- *2019.12* School First-class Scholarship (5%)
