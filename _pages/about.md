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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scalable Autoregressive Monocular Depth Estimation](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Scalable_Autoregressive_Monocular_Depth_Estimation_CVPR_2025_paper.html)

**Jinhong Wang**, Jian Liu, Dongqi Tang, Weiqiang Wang, Wentong Li, Danny Chen, Jintai Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/DAR) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:LkGwnXOMwfcC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:LkGwnXOMwfcC'></span></strong> 

![](https://img.shields.io/badge/Monocular Depth Estimation-224B8D) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024</div><img src='images/lkm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LKM-UNet: Large Kernel Vision Mamba UNet for Medical Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_34)

**Jinhong Wang**, Jintai Chen, Danny Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/LKM-UNet) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:ufrVoPGSRksC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:ufrVoPGSRksC'></span></strong> 

![](https://img.shields.io/badge/Medical Image Segmentation-224B8D) ![](https://img.shields.io/badge/Mamba-224B8D) 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/iccv2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ord2Seq: Regarding Ordinal Regression as Label Sequence Prediction](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Ord2Seq_Regarding_Ordinal_Regression_as_Label_Sequence_Prediction_ICCV_2023_paper.html)

**Jinhong Wang**, Yi Cheng, Jintai Chen, TingTing Chen, Danny Chen, Jian Wu

[🧑🏻‍💻 **Code**](https://github.com/wjh892521292/Ord2Seq) &ensp; [🌐 **Project Page**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=gyU139cAAAAJ&citation_for_view=gyU139cAAAAJ:zYLM7Y9cAGgC) <strong><span class='show_paper_citations' data='gyU139cAAAAJ:zYLM7Y9cAGgC'></span></strong> 

![](https://img.shields.io/badge/Ordinal Regression-224B8D) ![](https://img.shields.io/badge/Visual Rating-224B8D) 

</div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 




<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

