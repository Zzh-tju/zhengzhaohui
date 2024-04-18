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

Zhaohui Zheng received the M.S. degree in computational mathematics from Tianjin University in 2021, supervised by Prof. Ping Wang.
He is currently a Ph.D. candidate at Media Computing Lab, Nankai University, supervised by Prof. Ming-Ming Cheng and co-supervised by Asso. Prof. Qibin Hou.
His research interests include object detection, instance segmentation, and knowledge distillation.
He received the CCF-CV Academic Emerging Scholar Award in 2023.
 <a href='https://scholar.google.com/citations?user=0X71NDYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Citation"></a>。

## Research Interests：

My research interests are object detection, instance segmentation, and knowledge distillation. 

Specific directions: Loss function, Non-maximum suppression, Label assignment, Evaluation, Head network, and knowledge distillation in object detection.

See my recent publications for more details.

<span class='anchor' id='-fs'></span>

## News

+ I received the CCF-CV Academic Emerging Scholar Award in 2023.
+ One paper accepted by CVPR'24
+ One paper accepted by ICCV'23
+ One paper accepted by T-PAMI'23
+ One paper accepted by CVPR'22
+ One paper accepted by T-CYB'21
+ One paper accepted by AAAI'20

<span class='anchor' id='-group'></span>

## Collaborator

+ Ming-Ming Cheng
+ Qibin Hou
+ Xiang Li
+ Chenyu Ming
+ Jiabao Wang
+ Yuxuan Li
+ Jian Yang
  
+ Wangmeng Zuo
+ Dongwei Ren
  
+ Qinghua Hu
+ Ping Wang
+ Rongguang Ye
+ Wei Liu
  
+ Jinze Li


## Journal Publications ([Google Scholar](https://scholar.google.com/citations?user=0X71NDYAAAAJ&hl=en))

#### "*" means authors contributed equally and "#" means corresponding author.

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization distillation for object detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Rongguang Ye, Qibin Hou#, Dongwei Ren, Ping Wang, Wangmeng Zuo, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2204.05957.pdf">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Enhancing geometric factors in model learning and inference for object detection and instance segmentation</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Ping Wang, Dongwei Ren, Wei Liu, Rongguang Ye, Qinghua Hu, Wangmeng Zuo</p> 
  <p style="line-height:15px">IEEE Transactions on Cybernetics (TCYB), 2022</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2005.03572.pdf">[Arxiv]</a> <a href="https://github.com/Zzh-tju/CIoU" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

## Conference Publications ([Google Scholar](https://scholar.google.com/citations?user=0X71NDYAAAAJ&hl=en))

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Distance-IoU loss: Faster and better learning for bounding box regression</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Ping Wang, Wei Liu, Jinze Li, Rongguang Ye, Dongwei Ren</p> 
  <p style="line-height:15px">Proceedings of the AAAI Conference on Artificial Intelligence (AAAI), 2020</p>   
  <p style="line-height:15px"> <a href="https://doi.org/10.1609/aaai.v34i07.6999">[Arxiv]</a> <a href="https://github.com/Zzh-tju/DIoU">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Localization distillation for dense object detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>*, Rongguang Ye*, Ping Wang, Dongwei Ren, Wangmeng Zuo, Qibin Hou#, Ming-Ming Cheng</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2022</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Localization_Distillation_for_Dense_Object_Detection_CVPR_2022_paper.pdf">[Arxiv]</a> <a href="https://github.com/HikariTJU/LD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>CrossKD: Cross-Head Knowledge Distillation for Dense Object Detection</h4>   
  <sub><p style="line-height:15px"> Jiabao Wang*, Yuming Chen*, </b>Zhaohui Zheng</b>, Xiang Li, Ming-Ming Cheng, Qibin Hou#</p> 
  <p style="line-height:15px">IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2024</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2306.11369.pdf">[Arxiv]</a> <a href="https://github.com/jbwang1997/CrossKD">[Code]</a></p>   
  </sub>
</blockquote>

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Large selective kernel network for remote sensing object detection</h4>   
  <sub><p style="line-height:15px"> Yuxuan Li, Qibin Hou, </b>Zhaohui Zheng</b>, Ming-Ming Cheng, Jian Yang#, Xiang Li#</p> 
  <p style="line-height:15px">IEEE International Conference on Computer Vision (ICCV), 2023</p>   
  <p style="line-height:15px"> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Large_Selective_Kernel_Network_for_Remote_Sensing_Object_Detection_ICCV_2023_paper.pdf">[Arxiv]</a> <a href="https://github.com/VCIP-RGBD/DFormer">[Code]</a></p>   
  </sub>
</blockquote>

## Preprint

<blockquote style="color: black;  border-width: 8px; border-color: orange">   
  <h4>Zone Evaluation: Revealing Spatial Bias in Object Detection</h4>   
  <sub><p style="line-height:15px"> <b>Zhaohui Zheng</b>, Yuming Chen, Qibin Hou, Xiang Li, Ping Wang, Ming-Ming Cheng</p> 
  <p style="line-height:15px">Arxiv, 2023</p>   
  <p style="line-height:15px"> <a href="https://arxiv.org/pdf/2310.13215.pdf">[Arxiv]</a> <a href="https://github.com/Zzh-tju/ZoneEval" class="redlink">[Code]</a></p>   
  </sub>
</blockquote>

<span class='anchor' id='-services'></span>

## Academic Services

+ Reviewers for TPAMI/CVPR/NeurIPS/ICML etc.

<span class='anchor' id='-awards'></span>

## Honors and Awards

+ CCF-CV Academic Emerging Scholar Award, 2023.
