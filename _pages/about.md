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

Hi! I am currently working as a algorithm researcher in the <a href="https://www.jdl.com/IntelligenVehicle/">Autonomous Driving Division of X Research Department, JD Logistics</a>, mainly engaged in the research and development of vision and point cloud perception algorithms.  <br>

I obtained my master's degree from the School of Computer Science and Engineering, <b>Northeastern University</b>, Shenyang, China in 2023, advised by Professor <a href="http://www.cse.neu.edu.cn/2019/0312/c6641a157492/page.htm">Lu Wang (王璐)</a>. 
I also participated in <b>Tsinghua University</b>'s joint training of graduate students, with Professor<a href="http://www.svm.tsinghua.edu.cn/essay/80/1875.html"> Xinyu Zhang (张新钰)</a> and Academician of Chinese Academy of Engineering (CAE) <a href="https://www.tsinghua.edu.cn/info/1166/93890.htm"> Jun Li (李骏)</a> as my supervisor. 
During the joint training period, I was responsible for the algorithm research of the perception group, as well as the integration and debugging of each module system of the unmanned vehicle in the Meng Shi Team (清华猛狮团队).
Our team achieved significant accolades, including the gold medal in the 2021 World Intelligent Driving Challenge Extreme, first prize in the 2019 i-VISTA Automatic Driving Challenge Competition, and top honors in the City Traffic Scene Challenge Competition.

<p>My research interests lie in the application of deep learning to various computer vision tasks, with a focus on:
  <ul>
    <li>Autonomous driving perception algorithm.</li>
    <li>Multimodal Information Fusion.</li>
    <li>Zero/Few-shot Learning.</li>
  </ul>
</p>

# 🔥 News
- *2024.08* (*Pinned*): &nbsp;🔥🔥🔥 I'm excited to announce the release of a new repository on GitHub focused on various attention mechanisms! This repo is designed to make it easier to experiment with and integrate different attention modules, offering a plug-and-play approach to boost performance across tasks. <b>Check it out and feel free to get involved:</b> [Attention-Mechanisms](https://github.com/gongyan1/Attention-Mechanism-Pytorch)
- *2025.01*: &nbsp;🎉 One paper is accepted by **IEEE Transactions on Intelligent Transportation Systems** (中科院一区Top, IF=7.9). 
- *2024.10*: &nbsp;🎉 One paper is accepted by **IEEE Transactions on Geoscience and Remote Sensing** (中科院一区Top, IF=7.5). 
- *2024.07*: &nbsp;🎉 One paper is accepted by **Automotive Innovation** (中科院一区, IF=	4.8). 
- *2024.05*: &nbsp;🎉 One paper is accepted by **The 62nd Annual Meeting of the Association for Computational Linguistics (ACL 2024)** (CCF A). 
- *2024.02*: &nbsp;🎉 One paper is accepted by **IEEE Transactions on Intelligent Vehicles** (中科院一区Top, IF=14). 
- *2024.01*: &nbsp;🎉 One paper is accepted by **Engineering Applications of Artificial Intelligence** (中科院一区Top, IF=7.5). 
- *2023.06*: &nbsp;🎉 **Three papers** are accepted by **IEEE Transactions on Intelligent Vehicles** (中科院一区Top, IF=14).  
- *2023.05*: &nbsp;🎉 One paper is accepted by **IEEE Transactions on Computational Social Systems** (中科院二区, IF=5.1). 
- *2023.03*: &nbsp;🎉 One paper is accepted by **APPLIED INTELLIGENCE** (中科院二区, IF=5). 
- *2022.08*: &nbsp;🎉 One paper is accepted by **IEEE Transactions on Vehicular Technology** (中科院二区Top, IF=6.1).
- *2021.08*: &nbsp;🎉 One paper is accepted by **ICARM 2021 Best Paper**.


# 📝 Publications 
<b style="color:#FF5733;">Note: *, #, and bold text indicate equal contribution, corresponding author, and myself, respectively.</b>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2025</div><img src='images/IAF.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Steering Angle-Guided Multimodal Fusion Lane Detection for Autonomous Driving**](https://ieeexplore.ieee.org/document/10812657)

**Yan Gong**, Xinyu Zhang#, Jianli Lu, Xinmin Jiang, Zichen Wang, Hao Liu, Zhiwei Li, Li Wang, Qingshan Yang, Xingang Wu

published on <b>IEEE Transactions on Intelligent Transportation Systems</b>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC)  -->
[**Code**](https://github.com/gongyan1/IAFNet) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Steering+Angle-Guided+Multimodal+Fusion+Lane+Detection+for+Autonomous+Driving&btnG=) 
<!-- <strong><span class='show_paper_citations' data='YEI4sL4AAAAJ:Y0pCki6q_DkC'></span></strong> -->
- We are the first work to introduce steering angle in-formation into lane detection, which adopts LIA-CAM to fuse steering angle features with image features, allowing the network to exploit the implicit relationship between the two to assist lane detection in adverse lighting environments. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2024</div><img src='images/TCLaneNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**TCLaneNet: Task-Conditioned Lane Detection Network Driven by Vibration Information**](https://ieeexplore.ieee.org/document/10411125)

**Yan Gong**, Xinmin Jiang, Lu Wang#, Lisheng Xu, Jianli Lu, Hao Liu, Lei Lin, Xinyu Zhang

published on <b>IEEE Transactions on Intelligent Vehicles</b>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC)  -->
[**Code**](https://github.com/gongyan1/TCLaneNet) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=TCLaneNet%3A+Task-Conditioned+Lane+Detection+Network+Driven+by+Vibration+Information&btnG=) 
<!-- <strong><span class='show_paper_citations' data='YEI4sL4AAAAJ:Y0pCki6q_DkC'></span></strong> -->
- To deal with occlusion and low-light conditions in the lane detection, we first propose to utilize the vibration signals generated when vehicles pass over the vibration marking lines as supervision for lane occlusion prediction, whose features are then used to adaptively adjust the weights of lane detection network to improve its performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSS 2023</div><img src='images/SIFDriveNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SIFDriveNet: Speed and Image Fusion for Driving Behavior Classification Network**](https://ieeexplore.ieee.org/document/10225413)

**Yan Gong**\*, Jianli Lu\*; Wenzhuo Liu\*; Zhiwei Li#; Xinmin Jiang; Xin Gao; Xingang Wu

published on <b>IEEE Transactions on Computational Social Systems</b>

[**Code**](https://github.com/gongyan1/SIFDriveNet) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=SIFDriveNet%3A+Speed+and+Image+Fusion+for+Driving+Behavior+Classification+Network&btnG=) 
<!-- - Driving behavior classification is an important direction in the field of social transportation systems and advanced driving assistance system (ADAS).  -->
- We first introduce a 2D image with detailed roadside information and convert speeds into a 2D spectrogram using short-time Fourier transform (STFT) to represent their time-frequency characteristics, unifying the data space of image and speed information.
- A tensor fusion method based on weight decomposition is proposed to fully fuse the vectors of the two modalities, achieving leading performance on UAH-DriveSet and distracted driving multimodal dataset.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AUIN 2024</div><img src='images/SkipcrossNets.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SkipcrossNets: Adaptive Skip-cross Fusion for Road Detection**](https://arxiv.org/abs/2308.12863)

**Yan Gong**, Xinyu Zhang#, Hao Liu, Xinming Jiang, Zhiwei Li, Xin Gao, Lei Lin, Dafeng Jin, Jun Li, Huaping Liu

published on <b>Automotive Innovation</b>

<!-- [**Code**](https://github.com/gongyan1/Oblique-Convolution) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=SkipcrossNets%3A+Adaptive+Skip-cross+Fusion+for+Road+Detection&btnG=) 
- To address the challenges of pedestrian detection under insufficient nighttime illumination, we propose a Feature Aggregation Module (FAM) that adaptively captures cross-channel and cross-dimensional information interactions between two modes. 
- The proposed FAM module is embedded into a dual-stream network adapted from YOLOv5. The advantages of FANet are its small size (15 MB) and fast processing speed (8 ms per frame).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APIN 2023</div><img src='images/FANet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A Feature Aggregation Network for Multispectral Pedestrian Detection**](https://link.springer.com/article/10.1007/s10489-023-04628-y)

**Yan Gong**, Lu Wang#, Lisheng Xu 

published on <b>Applied Intelligence</b>

[**Code**](https://github.com/gongyan1/FANet) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=A+feature+aggregation+network+for+multispectral+pedestrian+detection&btnG=) 
- To address the challenges of pedestrian detection under insufficient nighttime illumination, we propose a Feature Aggregation Module (FAM) that adaptively captures cross-channel and cross-dimensional information interactions between two modes. 
- The proposed FAM module is embedded into a dual-stream network adapted from YOLOv5. The advantages of FANet are its small size (15 MB) and fast processing speed (8 ms per frame).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2023</div><img src='images/Vehicle_information_survey.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Multi-Modal Fusion Technology Based on Vehicle Information: A Survey**](https://ieeexplore.ieee.org/document/10104104)

Xinyu Zhang, **Yan Gong#**, Jianli Lu, Jiayi Wu, Zhiwei Li, Dafeng Jin, Jun Li

published on <b>IEEE Transactions on Intelligent Vehicles</b>

<!-- [**Code**](https://github.com/gongyan1/FANet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Multi-Modal+Fusion+Technology+Based+on+Vehicle+Information%3A+A+Survey&btnG=) 
- To address the challenges of pedestrian detection under insufficient nighttime illumination, we propose a Feature Aggregation Module (FAM) that adaptively captures cross-channel and cross-dimensional information interactions between two modes. 
- The proposed FAM module is embedded into a dual-stream network adapted from YOLOv5. The advantages of FANet are its small size (15 MB) and fast processing speed (8 ms per frame).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2023</div><img src='images/oblique_convolution.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Oblique Convolution: A Novel Convolution Idea for Redefining Lane Detection**](https://ieeexplore.ieee.org/document/10264148)

Xinyu Zhang, **Yan Gong#**, Jianli Lu, Zhiwei Li, Shixiang Li, Shu Wang, Wenzhuo Liu, Li Wang, Jun Li

published on <b>IEEE Transactions on Intelligent Vehicles</b>

[**Code**](https://github.com/gongyan1/Oblique-Convolution) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Oblique+Convolution%3A+A+Novel+Convolution+Idea+for+Redefining+Lane+Detection&btnG=) 
- To address the challenges of pedestrian detection under insufficient nighttime illumination, we propose a Feature Aggregation Module (FAM) that adaptively captures cross-channel and cross-dimensional information interactions between two modes. 
- The proposed FAM module is embedded into a dual-stream network adapted from YOLOv5. The advantages of FANet are its small size (15 MB) and fast processing speed (8 ms per frame).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI 2024</div><img src='images/GLMDriveNet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**GLMDriveNet: Global–local Multimodal Fusion Driving Behavior Classification Network**](https://www.sciencedirect.com/science/article/pii/S0952197623017591)

Wenzhuo Liu, **Yan Gong**, Guoying Zhang#, Jianli Lu, Yunlai Zhou, Junbin Liao

published on <b>Engineering Applications of Artificial Intelligence</b>

[**Code**](https://github.com/gongyan1/GLMDrivenet) ｜
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=GLMDriveNet%3A+Global%E2%80%93local+Multimodal+Fusion+Driving+Behavior+Classification+Network&btnG=) 
- We propose a Global-Local Multimodal Fusion Driving Behavior Classification Network (GLMDriveNet), which accurately classifies driver behavior into normal driving, aggressive driving, and fatigued driving, achieving state-of-the-art performance on the public UAH dataset. 
- A Global-Local Interaction Channel Attention Module (GLI-CAM) is introduced to extract effective features from roadside images and vehicle speed spectrograms, while a Multi-Scale Feature Representation Fusion Module (MS-FRFM) integrates high-scale and low-scale information, assigning varying importance to different modalities to enhance the network's focus on useful information.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVT 2022</div><img src='images/OpenMPD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**OpenMPD: An Open Multimodal Perception Dataset for Autonomous Driving**](https://ieeexplore.ieee.org/document/9682587)

Xinyu Zhang\*, Zhiwei Li#\*, **Yan Gong**\*, Dafeng Jin, Jun Li, Li Wang, Yanzhang Zhu, Huaping Liu

published on <b>IEEE Transactions on Vehicular Technology</b>

<!-- [**Code**](https://github.com/gongyan1/SIFDriveNet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=OpenMPD%3A+An+Open+Multimodal+Perception+Dataset+for+Autonomous+Driving&btnG=) 
- A multimodal perception benchmark for challenging examples is presented for the first time. Compared to existing datasets, OpenMPD places greater emphasis on complex urban scenarios, such as overexposed or dark environments, crowded areas, unstructured roads, and intersections. 
- Our data collection vehicle is equipped with 6 cameras and 4 LiDARs, capturing multimodal data with a 360-degree view. We also utilize a 128-beam LiDAR to provide high-resolution point clouds for a better understanding of the 3D environment and sensor fusion. More details can be found on http://www.openmpd.com/.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/AskOneTimes.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Just Ask One More Time! Self-Agreement Improves Reasoning of Language Models in (Almost) All Scenarios**](https://arxiv.org/abs/2311.08154)

Lei Lin\*, Jiayi Fu\*, Pengli Liu, Qingyang Li, **Yan Gong**\*, Junchen Wan, Fuzheng Zhang, Zhongyuan Wang, Di Zhang, Kun Gai

published on <b>The 62nd Annual Meeting of the Association for Computational Linguistics</b>

<!-- [**Code**](https://github.com/gongyan1/SIFDriveNet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Just+Ask+One+More+Time%21+Self-Agreement+Improves+Reasoning+of+Language+Models+in+%28Almost%29+All+Scenarios&btnG=) 
- To address the issues of repetitiveness and local optimality caused by naive greedy decoding in chain-of-thought (CoT) prompting, we propose a general ensemble optimization method. This method is applicable to nearly all types of input problem formats and scenarios where the reasoning path answers may be known or unknown.
- Our method demonstrates outstanding performance and exceptional generalization capabilities across six public reasoning benchmarks.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICARM 2021 Best Paper</div><img src='images/ICARM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Multi-modal attention guided real-time lane detection**](https://ieeexplore.ieee.org/document/9536157)

Xinyu Zhang#*, <b>Yan Gong*</b>, Zhiwei Li, Xuan Liu, Shuyue Pan and Jun Li

published on <b>IEEE International Conference on Advanced Robotics and Mechatronics </b>

<!-- [**Code**](https://github.com/gongyan1/SIFDriveNet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Multi-modal+attention+guided+real-time+lane+detection&btnG=) 
- We propose an effective real-time model for lane detection, using a fusion strategy to compensate for the limitations of single  mode  detection  and  applying  multi-frame  input  to solve  the  practical  problems  such  as vehicles  obstruction and mark degradation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/SparseDet.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SparseDet: A Simple and Effective Framework for Fully Sparse LiDAR-based 3D Object Detection**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10695153)

Lin Liu, Ziying Song, Qiming Xia, Feiyang Jia, Caiyan Jia, Lei Yang, <b>Yan Gong</b>, Hongyu Pan

published on <b>IEEE Transactions on Geoscience and Remote Sensing</b>

<!-- [**Code**](https://github.com/gongyan1/SIFDriveNet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=SparseDet%3A+A+Simple+and+Effective+Framework+for+Fully+Sparse+LiDAR-based+3D+Object+Detection&btnG=) 
- SparseDet introduces a novel approach to LiDAR-based sparse 3D object detection by using sparse queries as object proxies, enhancing contextual information aggregation through its Local Multi-scale Feature Aggregation (LMFA) and Global Feature Aggregation (GFA) modules. 
- Experiments show that SparseDet outperforms the previous best sparse detector, VoxelNeXt, by 2.2% mAP and achieves a faster inference speed of 13.5 FPS on nuScenes, while also surpassing the classical FSDV2 method in both accuracy and speed.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIV 2023</div><img src='images/TVGReID.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Tvg-reid: Transformer-based vehicle-graph re-identification**](https://ieeexplore.ieee.org/document/10173635)

Zhiwei Li, Xinyu Zhang#, Chi Tian, Xin Gao, <b>Yan Gong</b>, Jiani Wu, Guoying Zhang, Jun Li, and Huaping Liu

published on <b>IEEE Transactions on Intelligent Vehicles</b>

<!-- [**Code**](https://github.com/gongyan1/SIFDriveNet) ｜ -->
[**Cite**](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=Tvg-reid%3A+Transformer-based+vehicle-graph+re-identification&btnG=) 
- We propose a backbone network for vehicle re-identification that leverages CNN and Transformer feature extraction advantages, achieving superior performance by extracting detailed image features, while a vehicle knowledge graph transfer network enhances information correlation across different vehicle types.
</div>
</div>


# 📄 Patent
- 一种基于显著性图的多光谱融合行人检测方法及装置, 202310374850.7, 第一发明人，已授权。
-	一种图像和车速信息融合的驾驶行为分类方法及装置, CN115496978A, 第二发明人, 已授权。
-	基于深度学习的劳保用品佩戴情况检测和身份识别的方法, CN111488804A, 第三发明人, 已授权。
-	一种基于振动信号和RGB图像融合的语义分割方法及装置, CN114037834A, 第三发明人, 已授权。
-	基于注意力机制的融合网络车道线检测方法及终端设备, CN111950467A, 第四发明人, 已授权。

# 🎖 Honors and Awards
- *2024.02*, Won the Best Newcomer Award in the Autonomous Driving Department of X Divsion, JDL.
- *2023.10*, Won the top 45 in the "Black Horse" Competition in JD.
- *2022.06*, Won the top 10 in the 3D semantic segmentation of Waymo dataset.
- *2021.08*, Won the "Tomorrow's Star" honorary title at Tsinghua University.


# 📖 Educations
- *2020.09 - 2023.06*, Joint Master's Degree, Tsinghua University, Beijing. 
- *2020.09 - 2023.06*, Master, Northeastern University, Shenyang. 
- *2016.09 - 2020.06*, Undergraduate, Shanxi University, Taiyuan. 


# 💻 Internships
- *2022.01 - 2022.10*, Apollo (Baidu), Autonomous Driving Technology Department, China.
- *2021.11 - 2022.01*, Megvii, Development Product Department, China.
- *2021.07 - 2021.11*, JD, AI Research Institute, Multimedia and Video Algorithms Department, China.