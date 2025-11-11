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

I'm currently a fourth year undergrad at Peking University (PKU), advised by [Prof. Wentao Zhang](https://zwt233.github.io/). My primary research interests lie in data-centric machine learning and its applications in large language models (LLMs). In particular, I focus on how high-quality data can be leveraged to enhance models’ generalization and logical reasoning abilities. I am also interested in how LLM agents can perform decision-making and reasoning in complex, dynamic settings.

Prior to this, I worked in Prof. Yitao Liang's [CraftJarvis](https://craftjarvis.github.io/) Team, committed to developing a generalist agent capable of mastering a wide range of tasks and challenges within the open-world Minecraft.


# 🔥 News
- *2025.10*: &nbsp;🎉🎉 Our survey page of "Data-Centric Perspectives on Agentic Retrieval-Augmented Generation: A Survey" is out at [Awesome-AgenticRAG-Data](https://github.com/fatty-belly/Awesome-AgenticRAG-Data). 
- *2025.06*: &nbsp;🎉🎉 Our paper "Open-World Skill Discovery from Unsegmented Demonstration Videos" is accepted by ICCV 2025.  

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/SBD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span class="paper-title">Open-World Skill Discovery from Unsegmented Demonstration Videos</span>

**Jingwen Deng\***, Zihao Wang\*, Shaofei Cai, Anji Liu, Yitao Liang

[**Paper**](https://arxiv.org/pdf/2503.10684) \| [**Project**](https://craftjarvis.github.io/SkillDiscovery/) <strong><span class='show_paper_citations' data='7at7KbUAAAAJ:u-x6o8ySG0sC'></span></strong>
- We propose a self-supervised method, **Skill Boundary Detection (SBD)**, that segments unlabelled long videos into semantic aware skill-consistent parts by detecting prediction-error peaks.
- In Minecraft experiments, SBD significantly improves both short-term and long-horizon task performance, enabling effective use of diverse online videos to train instruction-following agents.
</div>
</div>

<div class='paper-box'>
<div markdown="1">

<span class="paper-title">LogicPuzzleRL: Cultivating Robust Mathematical Reasoning in LLMs via Reinforcement Learning</span>

Zhen Hao Wong\*, **Jingwen Deng\***, Runming He, Zirong Chen, Qijie You, Hejun Dong, Hao Liang, Chengyu Shen, Bin Cui, Wentao Zhang

**arXiv 2025** <strong><span class='show_paper_citations' data='7at7KbUAAAAJ:u5HHmVD_uO8C'></span></strong>

[**Paper**](https://arxiv.org/abs/2506.04821) \| [**Code**](https://github.com/wongzhenhao/GameRL)

</div>
</div>

# 📝 Works in Progress

<div class='paper-box'><div class='paper-box-image'><img src='images/agentic_rag_survey.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

<span class="paper-title">Data-Centric Perspectives on Agentic Retrieval-Augmented Generation: A Survey</span>

**Jingwen Deng**, Jihao Huang, Zhen Hao Wong, Hao Liang, Bin Cui, Wentao Zhang

[**Project**](https://github.com/fatty-belly/Awesome-AgenticRAG-Data)

This survey provides a data-centric overview of **Agentic RAG**, outlining its full data lifecycle and offering guidance for building scalable datasets to power adaptive, knowledge-seeking LLM agents.
</div>
</div>

# 🎖 Honors and Awards
- **2025**
  - Leo KoGuan Scholarship, Peking University
- **2024**
  - Leo KoGuan Scholarship, Peking University
  - First Prize, Mathematics competition of Chinese College Students
- **2023**
  - YanChuang Capital Scholarship, Peking University

# 📖 Educations
- *2022.09 -* , Peking University, BS in Computer Science
  - GPA: 3.834/4.0 (rank 9/146, top 7% in major)

# 💻 Internships
- *2025.09 -* , [DPTechnology](https://www.dp.tech/), China.