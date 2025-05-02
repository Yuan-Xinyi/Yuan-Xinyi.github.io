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

<span class='anchor' id='me'></span>

🙌Hi! I'm Xinyi Yuan, currently a Ph.D. candidate in [Harada Lab](https://www.roboticmanipulation.org/), Osaka University, supervised by [Prof. Weiwei Wan](https://wanweiwei07.github.io/). Previously, I got my MPhil degree at the Intelligent Transportation (INTR) Thrust in the Hong Kong University of Science and Technology (Guangzhou campus), supervised by [Prof. Meixin Zhu](https://meixinzhu.github.io/). I earned my Bachelor's in Robotics Engineering from Southern University of Science and Technology, exploring human-robot interaction strategies for upper-limb rehabilitation in [Brain-Robot Rehabilitation Technology Lab](https://zhangmmlab.com/). From Feb. 2024 to Sep. 2024, I remotely engaged in fascinating legged robot research at the [Shanghai AI laboratory](https://www.shlab.org.cn/) supervised by [Dr. Chenjia Bai](https://baichenjia.github.io/).

<span class='anchor' id='news'></span>

# ✨ News
- *2025.4*: &nbsp;📌 I started my Ph.D. in Harada Lab at Osaka University. 
- *2025.3*: &nbsp;🎉 We’ve released a new paper revisiting inverse kinematics with a [refined numerical solver](https://arxiv.org/abs/2503.22234).
- *2024.10*: &nbsp;📌 I joined Harada Lab at Osaka University as a research student. 
- *2024.10*: &nbsp;🎉 Please view our new work on diffusion-based locomotion policy on [project website](https://shangjaven.github.io/preference-aligned-diffusion-legged/).
- *2024.06*: &nbsp;📅 My MPhil graduate examination will be arranged on 2nd, July.
- *2024.04*: &nbsp;🎉 Our paper is accepted by the IEEE Transactions on Intelligent Vehicles.
- *2024.03*: &nbsp;🎉 Our paper is accepted by the 35th IEEE Intelligent Vehicles Symposiumk (IV 2024).

<span class='anchor' id='pub'></span>

# 📝Publications 
\* Co-first author, ✉️ Corresponding author.
- [**IKSel: Selecting Good Seed Joint Values for Fast Numerical Inverse Kinematics Iterations**](https://arxiv.org/abs/2503.22234)<br />
**<u>Xinyi Yuan</u>**\*, Weiwei Wan✉️, Kensuke Harada.<br />
***<font color = "#224B8D">Preprint. (Submitted to IEEE Transactions on Automation Science and Engineering)</font>***
- [**Preference Aligned Diffusion Planner for Quadrupedal Locomotion Control**](https://arxiv.org/abs/2410.13586)<br />
**<u>Xinyi Yuan</u>**\*, Zhiwei Shang\*, Zifan Wang, Chenkai Wang, Zhao Shan, Meixin Zhu✉️, Chenjia Bai✉️, Xuelong Li. <br />
***<font color = "#224B8D">arXiv preprint arXiv:2410.13586</font>***
- [**Effective Reinforcement Learning Control using Conservative Soft Actor-Critic.**](https://ieeexplore.ieee.org/abstract/document/10588807)<br />
Zhiwei Shang\*, **<u>Xinyi Yuan</u>**\*, Wenjun Huang, Meixin Zhu✉️, Chenjia Bai, Di Chen.  <br />
***<font color = "#224B8D">Preprint. (Submitted to IEEE Transactions on Automation Science and Engineering)</font>***
- [**AggFollower: Aggressiveness Informed Car-Following Modeling.**](https://ieeexplore.ieee.org/abstract/document/10490250)<br />
Xianda Chen, **<u>Xinyi Yuan</u>**, Meixin Zhu✉️, Xinhu Zheng, Shaojie Shen, Xuesong Wang, Yinhai Wang, Fei-Yue Wang.<br />
***<font color = "#224B8D">IEEE Transactions on Intelligent Vehicles (IF=14, JCR Q1)</font>***
- **Learning Realistic and Reactive Traffic Agents.**  <br />
Meixin Zhu✉️, Di Chen, **<u>Xinyi Yuan</u>**, Zhiwei Shang, Chenxi Liu.  
***<font color = "#224B8D">35th IEEE Intelligent Vehicles Symposium (IV 2024)</font>***

<span class='anchor' id='edu'></span>

# 👩‍🎓 Educations
- *Sep. 2022 - Jul. 2024*<br />
MPhil(Master of Philosophy), Intelligent Transportation Thrust, System Hub<br />
Hong Kong University of Science and Technology (Guangzhou campus). <br />
- *Sep. 2018 - Jun. 2022*<br />
Bachelor's Degree, Robotics Engineering, Department of Mechanical and Energy Engineering<br />
Southern University of Science and Technology.<br />

<span class='anchor' id='research'></span>

# 👩‍💻 Research Experience
- **Harada lab (Research Student)** <br />
Oct. 2024 - Apr. 2025<br />
Supervised by [Prof. Weiwei Wan](https://wanweiwei07.github.io/)<br />

- **Shang Hai AI laboratory (Remote Research)** <br />
Feb. 2024 - present<br />
Supervised by [Dr. Chenjia Bai](https://baichenjia.github.io/)<br />
Motivation: Improve the performance of the diffusion policy on high-frequency locomotion policy on legged robots.<br />
Main approaches: Propose the two-stage learning framework that combines the offline diffusion planner with online preference alignment.<br />

- **Drive AI laboratory, HKUST (GZ)** <br />
Dec. 2022 - present<br />
Supervised by [Prof. Meixin Zhu](https://meixinzhu.github.io/)<br />
Motivation: Incorporate driving aggressiveness into data-driven models, and realize safe and human-like driving behavior modeling.<br />
Main approaches: Embed aggressiveness tokens into Physics-Informed LSTM architecture, test on the Lyft and HighD datasets.<br />

- **Brain-Robot Rehabilitation Technology Lab, SUSTech** <br />
Sep. 2020 - Jun. 2022<br />
Supervised by [Prof. Mingming Zhang](https://zhangmmlab.com/)<br />
Motivation: Utilize online metabolic cost estimation to build a human-in-the-loop rehabilitation strategy.<br />
Main approaches: Use multimodal physiological signals to estimate metabolism by multiple linear regression, and design interaction strategies.<br />

- **Shenzhen Subway WebGIS Qualitative and Quantitative Hybrid Research** <br />
Sep. 2021 - Aug. 2022<br />
Supervised by [Prof. Lili Wang](https://www.sustech.edu.cn/en/faculties/wanglili.html)<br />
Field research, literature review, and geographic information visualization on Shenzhen's cultural landscape development.<br />

<span class='anchor' id='intern'></span>

# 👔 Internships
- **Gongzhiyi Technology Co., Ltd., Shenzhen** <br />
Jun.2022 - Aug. 2022<br />
User research, user education, and product design for the Series A+ funded blueprint management software "Evercraft."<br />
- **Guoxin Hongsheng Equity Investment Fund Management Co., Ltd., Shenzhen** <br />
Mar. 2021 - Jun. 2021<br />
Research intern, Private Equity Investment Department (IV)<br />