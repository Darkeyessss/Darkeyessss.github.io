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

Hi there!😊 I'm Kairan Dou, welcome to my personal website! Feel free to just call me Kevin. I am a junior undergraduate student majoring in Computer Science at Nankai University, currently an exchange student in the University of California, Berkeley. Since February 2025, I have been a Research Assistant at The University of Texas at Austin, working under the guidance of [Prof. Philipp Krähenbühl](https://www.philkr.net/), focusing on multimodal learning. Previously, I have conducted extensive research at the Visual Computing and Intelligent Perception(VCIP) Lab under the guidance of [Prof. Xiang Li](https://implus.github.io/).

My current research interests lie in:
- Reinforcement learning for stability and alignment in VLA models
- RL-augmented language model search and semantic retrieval
- Enhancing few-shot and zero-shot generalization in embodied agents


My broader goal is to establish scalable, unified post-training frameworks for embodied multi-modal agents, enabling both fine-grained reasoning and embodied decision-making through unified learning signals.

If you would like to connect further, feel free to contact me via email. 

You can also reach me **on WeChat** at: Darkeyes-

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 Our paper was accepted at FMEA Workshop @ CVPR 2025.
- *2025.02*: &nbsp;🎉🎉 I delivered an oral presentation at AAAI 2025 in Philadelphia.
- *2025.01*: &nbsp;🎉🎉 I arrived in Berkeley and commenced my exchange program.
- *2024.12*: &nbsp;🎉🎉 Our paper was accepted at AAAI 2025.

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FMEA Workshop</div><img src='images/ript.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interactive Post-Training for Vision-Language-Action Models](https://www.arxiv.org/pdf/2505.17016)

Shuhan Tan, **Kairan Dou**, Yue Zhao, Philipp Krähenbüh

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Introduces RIPT-VLA, a scalable third-stage reinforcement learning method for VLA models, enhancing performance through interactive training with sparse binary rewards.
- Demonstrates extraordinary efficiency by improving a near-unusable (4% success rate) supervised model to 97% success with just one demonstration in 15 iterations.
- Achieves SOTA performance across diverse benchmarks, including LIBERO-90 (94.3%), LIBERO-LONG 5-shot (71.4%), MetaWorld45 5-shot (76.0%), and OpenVLA-OFT (97.5%).
- Employs dynamic rollout sampling and leave-one-out advantage estimation to significantly enhance generalization, stability, and effectiveness across challenging tasks and scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Words to Worth: Newborn Article Impact Prediction with LLM](https://arxiv.org/pdf/2408.03934)

Penghai Zhao, Xinghua Xing, **Kairan Dou**, Jinyu Tian, Ying Tai, Jian Yang, Ming-Ming Cheng, Xiang Li

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Proposed the "Newborn Article Impact Prediction" (Newborn AIP) task and introduced the TNCSIsp metric, achieving an NDCG@20 score of 0.901.
- Constructed TKPD and NAID datasets, including over 12,000 samples for training and validation.
- Used LoRA to fine-tune and test 5+ large language models on server to evaluate prediction performance.
- Authored and finalized sections of the paper, ensuring academic writing standards.
</div>
</div>




# 📖 Educations

<div class='paper-box'><div class='paper-box-image'><img src='images/ucb.png' alt="sym" width="30%"></div>
<div class='paper-box-text' markdown="1">

*01/2025-05/2025*, Exchange Student, University of California, Berkeley.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/nku.png' alt="sym" width="30%"></div>
<div class='paper-box-text' markdown="1">

*09/2022-06/2026*, B.Eng. in Computer Science, Nankai University.
</div>
</div>


# 💻 Internships
- *2025.02 - present*, Research Assistant, The University of Texas at Austin, United States.
- *2024.06 - 2025.02*, VCIP Lab, Nankai University, China.
<!-- - *2024.06 - 2024.09*, Chinasoft International Co., Ltd., China.-->
<!-- - *2023.05 - 2023.08*, Beijing Advanced Digital Technology Co., Ltd., China.-->

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
- *2024.11*, Developed agent using retrieval-augmented generation system for detecting and evaluating open-source code in arXiv papers, leveraging GitHub APIs and abstract syntax tree similarity algorithms.
<!-- - *2024.10*, Agent-based technology for automatic author disambiguation and information generation. -->


<!-- 🎖 Honors and Awards*2024.08* Awarded Outstanding Individual for contributions to Chinasoft International Co., Ltd. *2024.02* Honorable Mention, Mathematical Contest in Modeling (MCM) -->




# 💡 Patents

- Patent pending: Agent-based retrieval-augmented generation system for detecting and evaluating open-source code in arXiv papers, utilizing GitHub APIs and abstract syntax tree similarity algorithms.

# 🏃‍♂️ Hobbies
- 🏸 Badminton: Played for approximately five years; member of the college team.​
- 🎸 Guitar: Served as the vice president of the Guitar Club.​
- 🎤 Singing: Recognized as one of the top ten singers in the college.​