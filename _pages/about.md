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

Liang Yao (姚亮) is from Jiuquan City (酒泉市), Gansu Province (甘肃省), and he loves fitness, traveling, and FPS games.  He is a first-year Ph.D. Student at [Hohai University (HHU)](https://www.hhu.edu.cn/), advised by [Prof. Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm) and [Prof. Chuanyi Zhang](https://ai.hhu.edu.cn/2023/0809/c17670a264073/page.htm). He is also a research intern at [COWARobot](https://www.cowarobot.com/). Before this, he received his B.Eng. and M.Eng. degree in Computer Science in 2022 and 2025 from Hohai University, where he was advised by [Prof. Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm).

# 🔍Research Topics

- **Remote Sensing Vision-Language Model**
- **UAV-based Multi-modal Perception**
- **AI Agent Workflow**

# 🔥 News
- *2025.08*: I earned Second Prize in the Outstanding Master's Thesis Award of the Jiangsu Province Instrumentation and Measurement Society. 
- *2025.08*: "UEMM-Air: Enable UAVs to Undertake More Multi-modal Tasks" is accepted by ACM MM 2025 Dataset Track! &nbsp;🎉🎉 
- *2025.07*: We introduce a geospatial reasoning workflow [RemoteReasoner](http://arxiv.org/abs/2507.19280). Model will be public available at next version.
- *2025.07*: "RemoteSAM: Towards Segment Anything for Earth Observation" is accepted by ACM MM 2025 (<b><font color="red">Oral</font></b>)! &nbsp;🎉🎉 
- *2025.06*: I earned my master's degree from HHU and was awarded the title of Outstanding Master's Graduate Student (<b><font color="red">7/234=3%</font></b>). &nbsp;🎓🎓
- *2025.05*: We introduce a referring expression segmentation-based unified paradigm and propose RemoteSAM, [paper](https://arxiv.org/abs/2505.18022) and [code](https://github.com/1e12Leon/RemoteSAM) is released.
- *2025.04*: "Boost UAV-based Object Detection via Scale-Invariant Feature Disentanglement and Adversarial Learning" is accepted by IEEE TGRS. &nbsp;🎉🎉 
- *2024.12*: "RemoteTrimmer: Adaptive Structural Pruning for Remote Sensing Image Classification" is accepted by IEEE ICASSP. &nbsp;🎉🎉 
- *2024.10*: "Domain-invariant Progressive Knowledge Distillation for UAV-based Object Detection" is accepted by IEEE GRSL. &nbsp;🎉🎉 


# 📖 Educations
- *2025.06 - Now*, Ph.D. at [AIMGroup](https://multimodality.group/), College of Computer Science and Software Engineering, Hohai University, supervised by [Prof. Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm) and [Prof. Chuanyi Zhang](https://ai.hhu.edu.cn/2023/0809/c17670a264073/page.htm).
- *2022.09 - 2025.06*, M.S. at [AIMGroup](https://multimodality.group/), College of Computer Science and Software Engineering, Hohai University, supervised by [Prof. Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm).
- *2018.09 - 2022.06*, B.S. at College of Computer Science and Information, Hohai University


# 💻 Internships
- *2025.06 - Now*, Research Intern at [COWARobot](https://www.cowarobot.com/), mentored by Dr. Pai Peng.

# 📝 Selected Publications 

\* Equal Contribution

## Remote Sensing Vision-Language Model

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025 oral</div><img src='images/RemoteSAM.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RemoteSAM: Towards Segment Anything for Earth Observation](https://arxiv.org/pdf/2505.18022)

 **Liang Yao**\*, Fan Liu\*, Delong Chen\*, Chuanyi Zhang, Yijun Wang, Ziyun Chen, Wei Xu, Shimin Di, Yuhui Zheng.

 [[**Code**]](https://github.com/1e12Leon/RemoteSAM) ![](https://img.shields.io/github/stars/1e12Leon/RemoteSAM?style=social)
 [[**Dataset**]](https://huggingface.co/datasets/1e12Leon/RemoteSAM_270K)
 [[极市平台]](https://mp.weixin.qq.com/s/caFm75zf5YEf8uwrWfsQTg)
[[我爱计算机视觉]](https://mp.weixin.qq.com/s/wNA42lEI-CEim_Tw1yCRnQ)
[[遥感与深度学习]](https://mp.weixin.qq.com/s/2xUJTyx-o8z1LE0-klXMxQ)
[[码科智能]](https://mp.weixin.qq.com/s/rg6JyAIENb0XTMfOu2KThw)

  - We propose a referring expression segmentation (RES) based unification paradigm and a robust yet visual foundation model, RemoteSAM.


</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/RemoteReasoner.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RemoteReasoner: Towards Unifying Geospatial Reasoning Workflow](https://arxiv.org/pdf/2507.19280)

 **Liang Yao**, Fan Liu, Hongbo Lu, Chuanyi Zhang, Rui Min, Shengxiang Xu, Shimin Di, Pai Peng.

</div>
</div>

## UAV-based Multi-modal Perception

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025 Dataset</div><img src='images/UEMM-Air.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UEMM-Air: Enable UAVs to Undertake More Multi-modal Tasks](https://arxiv.org/pdf/2406.06230)

 **Liang Yao**, Fan Liu, Shengxiang Xu, Chuanyi Zhang, Shimin Di, Xing Ma, Jianyu Jiang, Zequan Wang, Jun Zhou.

[[**Dataset**]](https://github.com/1e12Leon/UEMM-Air) ![](https://img.shields.io/github/stars/1e12Leon/UEMM-Air?style=social)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2025</div><img src='images/SIFDAL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boost UAV-Based Object Detection via Scale-Invariant Feature Disentanglement and Adversarial Learning](https://ieeexplore.ieee.org/abstract/document/10976665)

Fan Liu, **Liang Yao**, Chuanyi Zhang, Ting Wu, Xinlei Zhang, Xiruo Jiang, Jun Zhou.

[[**Code**]](https://github.com/1e12Leon/SIFDAL)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GRSL 2024</div><img src='images/PDIKD.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Domain-Invariant Progressive Knowledge Distillation for UAV-Based Object Detection](https://ieeexplore.ieee.org/abstract/document/10745610)

**Liang Yao**, Fan Liu, Chuanyi Zhang, Zhiquan Ou Ting Wu.

[[**Code**]](https://github.com/1e12Leon/PDIKD)

</div>
</div>

## 📃 Others 

- [RemoteTrimmer: Adaptive Structural Pruning for Remote Sensing Image Classification](https://ieeexplore.ieee.org/abstract/document/10890085). *In IEEE ICASSP2025*. Guangwenjie Zou\*, **Liang Yao**\*, Fan Liu, Chuanyi Zhang, Xin Li, Ning Chen, Shengxiang Xu, Jun Zhou.

- [AerialFace: A Light Weight Framework for Unmanned Aerial Vehicle Face Recognition](https://ieeexplore.ieee.org/abstract/document/10582027/). (Highlight) *In IEEE FG2024*. Zhiquan Ou\*, **Liang Yao**\*, Ting Wu, Fan Liu.

- [Chain-of-Talkers (CoTalk): Fast Human Annotation of Dense Image Captions](https://arxiv.org/pdf/2505.22627). *In arXiv25*. Yijun Shen, Delong Chen, Fan Liu, Xingyu Wang,
Chuanyi Zhang, **Liang Yao**, Yuhui Zheng.

# 🛠 Projects 

- Postgraduate Research and Practice Innovation Program of Jiangsu Province under Grant \| 江苏省研究生科研与实践创新项目 

# 👥 Co-authors

I assist Prof. [Fan Liu](https://cies.hhu.edu.cn/2024/0521/c21613a280137/page.htm) in supervising some undergraduate and graduate students:

[Shengxiang Xu](xushengxianggg.github.io), [Wei Xu](https://multimodality.group/author/%E8%AE%B8%E7%8E%AE/), [Rui Min](), [Rong Zhang](), [Ting Wu](https://multimodality.group/author/%E5%90%B4%E5%A9%B7/), [Yijun Wang](https://multimodality.group/author/%E7%8E%8B%E7%BF%8C%E9%AA%8F/), [Xiang Gu](), [Junjie Zhou]().


# 🎖 Honors and Awards

- 2025, Second Prize in the Outstanding Master's Thesis Award of the Jiangsu Province Instrumentation and Measurement Society \| 江苏省仪器仪表学会优秀硕士毕业论文二等奖 

- 2025, Outstanding Master's Graduate Student, Hohai University \| 河海大学优秀毕业研究生 

- 2024, Outstanding Graduate Student, Hohai University  \| 河海大学优秀研究生

- 2022-2024, First Prize of Academic Scholarship,  Hohai University \| 河海大学研究生一等奖学金

- 2024, Second Prize of Science and Technology Award (Scientific Innovation), Jiangsu Institute of Information Technology Application \| 江苏省信息技术应用学会科学技术奖（科技创新）二等奖

- 2024, Outstanding Poster Award, Jiangsu Graduate Academic Innovation Forum on Intelligent Control and Marine Information Processing \| 江苏省研究生智能控制与海洋信息处理前沿学术创新论坛优秀海报奖

- 2023, Outstanding Volunteer, Jiangsu Association for Artificial Intelligence \| 江苏省人工智能学会优秀志愿者

- 2018-2022, Outstanding Undergraduate Student Scholarship, Hohai University  \| 河海大学优秀学生奖学金

# 🏆 Competitions

- 2024, First Prize (Intelligent Transportation Track), National Final of Global Campus AI Algorithm Elite Competition \| 全球校园人工智能算法精英大赛智能交通赛道全国总决赛一等奖

- 2024, First Prize (Other Tracks), National Final of Global Campus AI Algorithm Elite Competition \| 全球校园人工智能算法精英大赛其他赛道全国总决赛一等奖

- 2023, Second Prize, Final of "Prospective Cup" Meta Intelligent Data Challenge \| "远见杯"元智能数据挑战赛决赛二等奖

- 2022, Third Prize, National Final of "China Software Cup" Software Design Competition \| "中国软件杯"大学生软件设计大赛总决赛三等奖

- 2021, Meritorious Winner, The Mathematical Contest in Modeling (MCM) \| 美国大学生数学建模大赛 Meritorious Winner

- 2021, Winning Solution Award, "Fight COVID-19 with Technology" Big Data Challenge (CCF Big Data & Computing Intelligence Contest) \| 中国计算机学会大数据与计算智能大赛"科技战疫"大数据公益挑战赛优胜方案奖

- 2021, Second Prize (Jiangsu Division), "Challenge Cup" National Undergraduate Academic Technology Works Competition \| "挑战杯"全国大学生课外学术科技作品竞赛江苏省二等奖


# 🔗 Academic Service
Reviewer: 
- AAAI Conference on Artificial Intelligence (**AAA26**)
- Conference on Computer Vision and Pattern Recognition (**CVPR25**)
- International Conference on Computer Vision (**ICCV25**)
- ACM International Conference on Multimedia (**ACMMM25**)
