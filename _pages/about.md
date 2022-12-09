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

<span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>

I am a Ph.D. candidate in the Department of Automation, Tsinghua University. As a member of [CFINS](http://cfins.au.tsinghua.edu.cn/en/), I'm supervised by [Prof. Qianchuan Zhao](http://cfins.au.tsinghua.edu.cn/personalhg/zhaoqc/). I received my Bachelor of Engineering degree from Department of Automation, Beijing University of Posts and Telecommunications (BUPT)  in 2018. 

My research interest lies in smart building and deep learning, including building occupancy detection/estimation, computer vision and generative model. 
I have published more than 10 papers at top international journals, including *Building and environment, Energy and buildings, Cell Patterns*.


# 🔥 News
- *2022.11*: 🎉🎉  Cell Press reported our work.[Report link](https://mp.weixin.qq.com/s/jDRYjovXeBpyaED2dH1z2Q).
- *2022.12*: 🎉🎉  Our large head tracking dataset (includs 2 millions head boxes) is completed, and will be available soon: **Kailai Sun**, Shaobo Liu, Gao Huang, Qianchuan Zhao. A large vision dataset for head tracking in dense crowd.
- *2022.12*: Our invited article will be completed. Protocol for Honeycomb: Application and Validation. Tian Xing\*, Hu Yan\*, **Kailai Sun**\*, Qianchuan Zhao. Star Protocols(Cell Sub-publication)


# 📝 Publications 

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
-->

## Under-review Papers
- [Integrating Machine Learning and Mathematical Optimization for Job Shop Scheduling](https://www.techrxiv.org/articles/preprint/Integrating_Machine_Learning_and_Mathematical_Optimization_for_Job_Shop_Scheduling/20510841). Anbang Liu, Peter B. Luh, **Kailai Sun**. *IEEE Transactions on Automation Science and Engineering* (**TASE**). (2022).(**Top** , SCI, IF:6.636). 

- A Comprehensive Review of AIoT-based Edge Devices and Lightweight Deployment. **Kailai Sun**, Xinwei Wang\*, Qianchuan Zhao. *IEEE Internet of Things Journal* (**IoTJ**). (2022).(**Top** , SCI, IF:**11.043**).
- [MITP-Net: a Deep-learning Framework for Short-term Indoor Temperature Predictions in Multi-zone Buildings.](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4289282) Tian Xing,**Kailai Sun**, Qianchuan Zhao.*Building and Environment* (**BAE**). (2022).(**Top** , SCI, IF:**7.201**).


## Journal Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ENB 2020</div><img src='/images/paper/2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [A review of building occupancy measurement systems](https://www.sciencedirect.com/science/article/abs/pii/S0378778819332918). \\
 **Kailai Sun**, Qianchuan Zhao, Jianhong Zou. *Energy and Buildings* (**ENB**). 216 (2020): 109965. (**Top** , SCI, IF:**7.093**, citations:**69**).  
- Five-years occupancy measurement systems based on cameras, WiFi, PIR sensors, CO2 sensors, electricity sensors are analyzed and discussed.
- The first comprehensive analysis based on different types and installed locations of camera.
  
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cell Patterns 2022</div><img src='/images/paper/HONEYCOMB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [Honeycomb: An open-source distributed system for smart buildings](https://www.sciencedirect.com/science/article/pii/S2666389922002306).  Tian Xing\*, Hu Yan\*, **Kailai Sun**\*, Yifan Wang, Xuetao Wang and Qianchuan Zhao. **Cell Patterns**(Cell Sub-publication)(2022). [Data link.](https://zenodo.org/record/7047167#.Yyu0AqRBzD4) [Code link.](https://zenodo.org/record/7047159#.Yyuz-KRBzD4)
- A bee-inspired, fully distributed, and open-source building IoT solution, has strong flexibility and robustness, multiple functionalities.
- Proposed vision-based deep-learning occupancy measurement system.
- High user acceptance during long-term stable operation.

  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BAE 2022</div><img src='/images/paper/DBF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- [A Fusion Framework of Vision-based Indoor Occupancy Estimation](https://www.sciencedirect.com/science/article/pii/S0360132322008617). \\
  **Kailai Sun**\*, Peng Liu\*, Tian Xing, Qianchuan Zhao and Xinwei Wang. *Building and Environment* (**BAE**). 222 (2022): 109354.(**Top** , SCI, IF:**7.201**). [Code link.](https://github.com/kailaisun/FFO)
- The first work to develop a three-level fusion framework in vision-based indoor occupancy estimation.
- Our framework achieves state-of-the-art (SOTA) performance through ablation studies on practical building surveillance videos.
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BAE 2022</div><img src='/images/paper/MPSN.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
 

- [MPSN: Motion-aware Pseudo-Siamese Network for Indoor Video Head Detection in Buildings](https://www.sciencedirect.com/science/article/abs/pii/S036013232200587X). **Kailai Sun**\*, Xiaoteng Ma\*, Peng Liu\*, Qianchuan Zhao. *Building and Environment* (**BAE**). 222 (2022): 109354.(**Top** , SCI, IF:**7.201**).[Code link.](https://github.com/pl-share/MPSN)
- The first work to jointly train the current frame and the pixel-level motion information into an end-to-end CNN network in head detection.
- We validate its robustness through adversarial experiments with a mathematical solution of small perturbations.
  
</div>
</div>

  

- [Indoor occupancy measurement by the fusion of motion detection and static estimation](https://www.sciencedirect.com/science/article/abs/pii/S037877882100877X). **Kailai Sun**, Qianchuan Zhao, Ziyou Zhang, and Xinyuan Hu. *Energy and Buildings* (**ENB**). 254 (2022): 111593.(**Top** , SCI, IF:**7.093**, citations:10).


- [Using knowledge inference to suppress the lamp disturbance for fire detection](https://www.sciencedirect.com/science/article/pii/S266644962100027X). **Kailai Sun**, Qianchuan Zhao, and Xinwei Wang. *Journal of Safety Science and Resilience* (**JSSR**). 2.3 (2021): 124-130.[Code link.](https://github.com/kailaisun/fire-detection-without-lamp)



 
## Conference Papers
- [Attendance and security system based on building video surveillance](https://drive.google.com/file/d/15HeVSLDb8vI0WaSrlMJJu7kj2qGIlVk4/view). **Kailai Sun**, Qianchuan Zhao, Jianhong Zou, Xiaoteng Ma. *International Conference on Smart City and Intelligent Building* (**ICSCIB**). Springer, Singapore, 2018. (citations:11).

- [Visual feedback system for traditional chinese medical massage robot](https://ieeexplore.ieee.org/abstract/document/8866076). **Kailai Sun**, Qianchuan Zhao, Zhenming Yang, Xiuwei Xu. *In 2019 Chinese Control Conference* (**CCC**). pp. 6379-6385. IEEE, 2019.[Code link.](https://github.com/kailaisun/New-two-dimensional-code_QR-code)

- [A multi-objective optimization of PV/ST-GSHP system based on office buildings](https://www.sciencedirect.com/science/article/pii/S1876610218306052). Yu Fu, Haiyang Lin, **Kailai Sun**, Qie Sun, Ronald Wennersten. *Energy Procedia*. 152 (2018): pp. 71-76.

- Research on Multi-temporal Cloud Removal using D-S Evidence Theory and Cloud Segmentation Model. Xinwei Wang\*, **Kailai Sun**\*, Qianchuan Zhao, and Jianhong Zou. *The CAAI International Conference on Artificial Intelligence* (**CICAI**). 2022. Accepted. 




<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>



- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 💻 Projects
- New generation intelligent building platform (National Key Research and Development Project of China under Grant 2017YFC0704100)
- Energy Internet Planning, Operation and Trading (National Key Research and Development Project of China under Grant 2016YFB0901900)
- National Natural Science Foundation of China under Grant No. 62192751 and 61425024
- The 111 International Collaboration Program of China under Grant No. BP2018006
- Satellite remote sensing image interpretation technology and system based on artificial intelligence (2019 Major Science and Technology Program for the Strategic Emerging Industries of Fuzhou, Grant BNR2019TD01009)
- The National Innovation Center of High Speed Train R&D project (CX/KJ-2020-0006)
- Huawei company-Control security issue literature research project
- Qiyuan Lab xxx project
- Ridar-based road vehicle counting and intelligent video surveillance system project 






# ✈ Internships
- *2021.06 - 2021.08*, Harbin Institute of Technology Robotics Research Institute Co., Ltd, Yangzhou. 

# 👨🏽‍🤝‍👨🏼 Collaborators
- [Qianchuan Zhao](http://cfins.au.tsinghua.edu.cn/personalhg/zhaoqc/) -  Professor, Department of Automation, Tsinghua University. 
- [Peter Luh](https://www.ee.uconn.edu/peter-b-luh/) - Professor, Board of Trustees Distinguished Professor Emeritus, University of Connecticut.
- Shaobo Liu -   Associate Professor, Intelligent Transportation Systems Research Center, Wuhan University of Technology.
- [Xiaoteng Ma](https://xtma.github.io/) -  Ph.D. candidate , Department of Automation, Tsinghua University. 
- Anbang Liu -  Ph.D. candidate , Department of Automation, Tsinghua University. 


# 🎖 Honors and Awards
- *2022.11* Tsinghua University - Lingjun Pilot Scholarship
- *2019.10* The first prize of Tsinghua University Comprehensive Excellent Scholarship (Top 1%)
- *2018.06*	Outstanding graduates of Beijing ordinary colleges and universities (Top 1%)
- *2022* Best Researcher Award for the contribution and honourable achievement in innovative research. International Research Awards on New Science Inventions NESIN 2022 Awards.
- *2015.11*	The second prize of the 7th National College Students Mathematics Competition
- *2016.06* The first prize in the Beijing Division of the 2016 National Mathematical Contest in Modeling for College Students
- *2015.11* The first prize of the first engineering design expression competition of BUPT (Top 1%)
- *2015.06/2016.06* Haohan company Scholarship (Top 1%)
- *2016.07* The second prize in the Beijing Division of the 2016 National Undergraduate Electronic Design Competition
- *2017* American Undergraduate Mathematical Contest in Modeling Honorable Mention 



# 📖 Educations
- *2018.09 - present*, Ph.D., Department of Automation, Tsinghua University.
- *2015.09 - 2018.06*,Ye Peida lab, Beijing University of Posts and Telecommunications (BUPT).
- *2014.09 - 2018.06*, Bachelor, Department of Automation, Beijing University of Posts and Telecommunications (BUPT).

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->


## 📞 Contact

[Department of Automation](https://www.au.tsinghua.edu.cn/) \
[Tsinghua University](https://www.tsinghua.edu.cn/en/) \
FIT Building 3-624 \
Beijing, China, 100084 \
E-mail: <skl18@mails.tsinghua.edu.cn> &emsp;<18813126518@163.com>\
     &emsp;  

