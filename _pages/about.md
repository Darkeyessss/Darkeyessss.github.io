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

Hi there!😊 I'm Kairan Dou, welcome to my personal website! Feel free to just call me Kevin. 

I am a junior undergraduate student majoring in Computer Science at Nankai University, and I have just completed my exchange program at the University of California, Berkeley.

This summer, I am working as a research intern at the both [MIT Media Lab](https://www.media.mit.edu/) and [Harvard Ophthalmology AI Lab](https://ophai.hms.harvard.edu/) under the joint supervision of [Prof.Paul Liang](https://pliang279.github.io/) and [Prof.Mengyu Wang](https://ophai.hms.harvard.edu/team/dr-wang/), where I focus on robotic manipulation. Since February 2025, I have been a Research Assistant at The University of Texas at Austin, working under the guidance of [Prof. Philipp Krähenbühl](https://www.philkr.net/), focusing on multimodal learning. Previously, I have conducted extensive research at the Visual Computing and Intelligent Perception(VCIP) Lab, advised by [Prof. Xiang Li](https://implus.github.io/).

My current research interests lie in:
- Reinforcement learning for stability and alignment in VLA models
- Enhancing few-shot and zero-shot generalization in embodied agents
<!-- - RL-augmented language model search and semantic retrieval -->

I aim to develop embodied agents with the capacity for generalizable reasoning and long-horizon decision-making.
My long-term vision is to advance the foundations of real-world intelligence through unified perception, control, and learning.

If you would like to connect further, feel free to contact me via email. 

You can also reach me **on WeChat** at: Darkeyes-

# 🔥 News

- *2025.05*: &nbsp;🎉🎉 Our paper was accepted at FMEA Workshop @ CVPR 2025.
- *2025.02*: &nbsp;🎉🎉 I delivered an oral presentation at AAAI 2025 in Philadelphia.
- *2024.12*: &nbsp;🎉🎉 Our paper was accepted at AAAI 2025.

# 📝 Publications 


<div class='paper-box'>
  <!-- ① 把包裹图片的 div 固定成一个更小的宽度 -->
  <div class='paper-box-image' style="flex:0 0 320px; max-width:320px; margin-right:7px;">
    <div>
      <div class="badge">FMEA Workshop</div>
      <!-- ② 图片宽度继续占满自己的列即可 -->
      <img src='images/ript.png' alt="sym" style="width:100%;">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

## [Interactive Post-Training for Vision-Language-Action Models](https://www.arxiv.org/pdf/2505.17016)

Shuhan Tan, **Kairan Dou**, Yue Zhao, Philipp Krähenbüh

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Introduces RIPT-VLA, a scalable third-stage reinforcement learning method for VLA models, enhancing performance through interactive training with sparse binary rewards.
- Achieves SOTA performance across diverse benchmarks, including LIBERO-90 (94.3%), LIBERO-LONG 5-shot (71.4%), MetaWorld45 5-shot (76.0%), and OpenVLA-OFT (97.5%).
- Employs dynamic rollout sampling and leave-one-out advantage estimation to significantly enhance generalization, stability, and effectiveness across challenging tasks and scenarios.
</div>
</div>

<div class='paper-box'>
  <!-- ① 把包裹图片的 div 固定成一个更小的宽度 -->
  <div class='paper-box-image' style="flex:0 0 320px; max-width:320px; margin-right:7px;">
    <div>
      <div class="badge">AAAI 2025</div>
      <!-- ② 图片宽度继续占满自己的列即可 -->
      <img src='images/1.png' alt="sym" style="width:100%;">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

## [From Words to Worth: Newborn Article Impact Prediction with LLM](https://arxiv.org/pdf/2408.03934)

Penghai Zhao, Xinghua Xing, **Kairan Dou**, Jinyu Tian, Ying Tai, Jian Yang, Ming-Ming Cheng, Xiang Li

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed the "Newborn Article Impact Prediction" (Newborn AIP) task and introduced the TNCSIsp metric, achieving an NDCG@20 score of 0.901.
- Constructed TKPD and NAID datasets, including over 12,000 samples for training and validation.
- Used LoRA to fine-tune and test 5+ large language models on server to evaluate prediction performance.
</div>
</div>




# 📖 Educations

&nbsp;

<!-- 图片 + 两行文字并排 -->
<div style="display:flex; align-items:center;">

  <!-- 左边图片列；多加一个 margin-right 调整间距 -->
  <img src="images/ucb.png"
       width="92"
       alt="UCB logo"
       style="flex:0 0 92px; margin-right:50px;">

  <!-- 右边文字列 -->
  <div style="line-height:1.4;">
    <strong style="font-size:1.2em;">University&nbsp;of&nbsp;California,&nbsp;Berkeley</strong><br>
    <em>01/2025-05/2025</em><br>
    <em>Exchange&nbsp;Student</em>
  </div>

</div>


&nbsp;



<!-- 图片 + 两行文字并排 -->
<div style="display:flex; align-items:center;">

  <!-- 左边图片列；多加一个 margin-right 调整间距 -->
  <img src="images/nku.png"
       width="92"
       alt="nku logo"
       style="flex:0 0 92px; margin-right:50px;">

  <!-- 右边文字列 -->
  <div style="line-height:1.4;">
    <strong style="font-size:1.2em;">Nankai&nbsp;University</strong><br>
    <em>09/2022-06/2026</em><br>
    <em>B.Eng.&nbsp;in&nbsp;Computer&nbsp;Science</em>
  </div>

</div>






# 💻 Internships


&nbsp;

<!-- 联合实习 MIT + Harvard -->
<div style="display:flex; align-items:center;">

  <!-- MIT logo -->
  <img src="images/mit.png"
       width="75"
       alt="MIT logo"
       style="flex:0 0 75px; margin-right:25px;">

  <!-- Harvard logo -->
  <img src="images/harvard.png"
       width="75"
       alt="Harvard logo"
       style="flex:0 0 75px; margin-right:35px;">

  <!-- 描述文字 -->
  <div style="line-height:1.4;">
    <strong style="font-size:1.2em;">
      MIT Media Lab & Harvard Ophthalmology AI Lab
    </strong><br>
    <em>2025.06 – present</em><br>
    <em>Research Intern (joint appointment)</em><br>
  </div>

</div>

&nbsp;

<!-- 图片 + 两行文字并排 -->
<div style="display:flex; align-items:center;">

  <!-- 左边图片列；多加一个 margin-right 调整间距 -->
  <img src="images/ut.png"
       width="97"
       alt="UCB logo"
       style="flex:0 0 97px; margin-right:45px;">

  <!-- 右边文字列 -->
  <div style="line-height:1.4;">
    <strong style="font-size:1.2em;">The University of Texas at Austin</strong><br>
    <em>2025.02 - present</em><br>
    <em>Research Assistant</em>
  </div>

</div>

&nbsp;

<!-- 图片 + 两行文字并排 -->
<div style="display:flex; align-items:center;">

  <!-- 左边图片列；多加一个 margin-right 调整间距 -->
  <img src="images/nku.png"
       width="92"
       alt="UCB logo"
       style="flex:0 0 92px; margin-right:50px;">

  <!-- 右边文字列 -->
  <div style="line-height:1.4;">
    <strong style="font-size:1.2em;">VCIP Lab, Nankai University</strong><br>
    <em>2024.06 - 2025.02</em><br>
    <em>Research Assistant</em>
  </div>

</div>

<!-- <img src="images/ut.png" width="97" alt="UT logo"> <span style="margin-left: 38px;"></span> *2025.02 - present*, Research Assistant, The University of Texas at Austin, United States

<img src="images/nku.png" width="92" alt="NKU logo">  <span style="margin-left: 43px;"></span> *2024.06 - 2025.02*, VCIP Lab, Nankai University, China -->
<!-- - *2024.06 - 2024.09*, Chinasoft International Co., Ltd., China.-->
<!-- - *2023.05 - 2023.08*, Beijing Advanced Digital Technology Co., Ltd., China.-->

<!-- 
# 💬 Projects

<div class='paper-box'><div class='paper-box-image'><img src='images/Poster.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

JobForce.AI

LLM-Powered Multi-Agent Platform for Job Seekers

**Kairan Dou**, Mingxi Tang , Yiya You, Yufeng Yan

- End-to-end LLM-powered pipeline automates both resume rewriting and job matching in a single workflow.
- Context-aware resume optimization tailors each experience using representative job descriptions and LLM-generated language.
- Semantic embedding–driven selection ranks and condenses content based on normalized cosine similarity for maximum relevance.
- Real-time, personalized job recommendations match optimized resumes against live postings filtered by user preferences.
- Quantitative alignment evaluation delivers a clear 100-point score and visual feedback on resume–JD fit improvements.
</div>
</div>


- *2024.06 - 2025.02*, Development of the AI for Research Service App, an automated arXiv paper selection platform that utilizes algorithms to provide users with the latest curated arXiv paper summaries and explanations.
- *2024.11*, Developed agent using retrieval-augmented generation system for detecting and evaluating open-source code in arXiv papers, leveraging GitHub APIs and abstract syntax tree similarity algorithms. -->
<!-- - *2024.10*, Agent-based technology for automatic author disambiguation and information generation. -->


<!-- 🎖 Honors and Awards*2024.08* Awarded Outstanding Individual for contributions to Chinasoft International Co., Ltd. *2024.02* Honorable Mention, Mathematical Contest in Modeling (MCM) -->



# 🏃‍♂️ Hobbies
- 🏸 Badminton: Men’s Singles and Doubles Champion of the College.​
- 🎸 Guitar: Served as the vice president of the Guitar Club.​
- 🎤 Singing: Recognized as one of the top ten singers in the college.​