---
permalink: /
title: ""
excerpt: ""
lang: en
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
I am currrently 2 Grade Master's student at Beijing University of Posts and Telecommunications (BUPT), advised by Prof. Haihong E.

My research interest includes multi-modal large language models (MLLMs) reasoning. I have published several papers at the top international AI conferences.
<!-- With a total of <a href='https://scholar.google.com/citations?user=jc4VYzMAAAAJJ'>google scholar citations <strong><span id='total_cit'>…</span></strong></a> (<a href='https://scholar.google.com/citations?user=jc4VYzMAAAAJJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations badge"></a>). -->

# 📖 Educations
* M.S. in School of Computer Science, Beijing University of Posts and Telecommunications, Computer Technology, 2024.09-2027.07(expected)
* B.S. in School of Computer Science, Beijing University of Posts and Telecommunications, Data Science And Big Data Technology, 2020.09-2024.07

# 🔥 News
- *2026.04*: &nbsp,🎉🎉 AEGIS: A Holistic Benchmark for Evaluating Forensic Analysis of AI-Generated Academic Images submitted to ACL 2026(Main Conference). 
- *2026.01*: &nbsp;🎉🎉 THEMIS: Towards Holistic Evaluation of MLLMs for Scientific Paper Fraud Forensic submitted to ICLR 2026(Poster).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/themis_poster.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[THEMIS: Towards Holistic Evaluation of MLLMs for Scientific Paper Fraud Forensic](https://openreview.net/attachment?id=y3UkklvoW9&name=pdf)

**Tzu-Yen Ma\***, Bo Zhang\*, Zichen Tang, Junpeng Ding, Haolin Tian, Yuanze Li, Zhuodi Hao, Zixin Ding, Zirui Wang, Xinyu Yu, Shiyao Peng, Yizhuo Zhao, Ruomeng Jiang, Yiling Huang, Peizhi Zhao, Jiayuan Chen, Weisheng Tan, Haocheng Gao, Yang Liu, Jiacheng Liu, Zhongjun Yang, Jiayu Huang, Haihong E

[**Home page**](https://github.com/BUPT-Reasoning-Lab/THEMIS)
[**Google Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=jc4VYzMAAAAJ&citation_for_view=jc4VYzMAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='jc4VYzMAAAAJ:d1gkVwhDpl0C'></span></strong>

-  We present THEMIS, a holistic multi-task benchmark of over 4000 questions derived from authentic retracted-paper cases and realistically simulated synthetic data, to systematically evaluate the fine-grained visual fraud reasoning abilities of MLLMs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/aegis_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AEGIS: A Holistic Benchmark for Evaluating Forensic Analysis of AI-Generated Academic Images](https://openreview.net/pdf?id=RW5pytG5nu)

Bo Zhang\*, **Tzu-Yen Ma\***, Zichen Tang, Junpeng Ding, Zirui Wang, Yizhuo Zhao, Peilin Gao, Zijie Xi, Zixin Ding, HaiyangSun, Haocheng Gao, Yuan Liu, Liangjia Wang, Yiling Huang, Yujie Wang, Yuyue Zhang, Ronghui Xi, Yuanze Li, Jiacheng Liu, Zhongjun Yang, Haihong E

-  We introduce AEGIS, a holistic benchmark for evaluating expert-level forensic reasoning on AI-generated academic images, advancing domain-specific complexity, diverse forgery simulations, and multi-dimensional forensic evaluation.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards

- *2025.4*  National Grand Champion, The 4th "Wutong Cup" Big Data Innovation & Maker Marathon Competition, China Mobile, 2025.04
 <!-- (第四届中国移动“梧桐杯”大数据创新大赛暨大数据创客马拉松大赛 全国总冠军) -->

# 🛠 Skills
- **Language:** Python, SQL, C
- **Deep Learning:** PyTorch, HuggingFace Transformers, vLLM
- **LLM:** Data Cleaning and Pre-processing for Pre-training and SFT、LoRA fine-tuning、prompt engineering
- **多模态工具:** OpenCV, CLIP, Segment Anything (SAM)

# 💬 Invited Talks

- *2026.4*, AITIME Forum / AITIME 论道, ICLR 2026 预讲会 北京邮电大学 BUPT ReasoningLab专场. \| [\[video\]](https://www.bilibili.com/video/BV12WoTBuETn/?spm_id_from=333.1387.collection.video_card.click) 

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->