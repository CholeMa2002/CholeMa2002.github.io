---
permalink: /zh/
title: ""
excerpt: ""
lang: zh
author_profile: true
redirect_from:
  - /zh/about/
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}
[Get My Resume (PDF)]
<span class='anchor' id='about-me'></span>
现为北京邮电大学计算机学院硕士研究生二年级，师从鄂海红教授，位于Reasoning Lab。

研究方向为多模态大语言模型（MLLM）推理与科学图像伪造取证。已在国际人工智能顶会发表多篇论文。
 <a href='https://scholar.google.com/citations?user=jc4VYzMAAAAJJ'>Google Scholar 引用累计 <strong><span id='total_cit'>21</span></strong></a>（<a href='https://scholar.google.com/citations?user=jc4VYzMAAAAJJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations" alt="Google Scholar citations badge"></a>）。

# 📖 教育背景
{: #-educations }

* 北京邮电大学计算机学院，计算机技术，硕士，2024.09–2027.07（预计）
* 北京邮电大学计算机学院，数据科学与大数据技术，学士，2020.09–2024.07

# 🔥 动态
{: #-news }

- *2026.04*：🎉 AEGIS：面向 AI 生成学术图像取证的综合评测基准，投稿 ACL 2026（主会）。
- *2026.01*：🎉 THEMIS：面向科学论文造假取证的多模态大模型综合评测，投稿 ICLR 2026（海报）。

# 📝 论文
{: #-publications }

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/themis_poster.png' alt="THEMIS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[THEMIS: Towards Holistic Evaluation of MLLMs for Scientific Paper Fraud Forensic](https://openreview.net/attachment?id=y3UkklvoW9&name=pdf)

**Tzu-Yen Ma\***, Bo Zhang\*, Zichen Tang, Junpeng Ding, Haolin Tian, Yuanze Li, Zhuodi Hao, Zixin Ding, Zirui Wang, Xinyu Yu, Shiyao Peng, Yizhuo Zhao, Ruomeng Jiang, Yiling Huang, Peizhi Zhao, Jiayuan Chen, Weisheng Tan, Haocheng Gao, Yang Liu, Jiacheng Liu, Zhongjun Yang, Jiayu Huang, Haihong E

[**项目主页**](https://github.com/BUPT-Reasoning-Lab/THEMIS)
[**Google Scholar**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-TW&user=jc4VYzMAAAAJ&citation_for_view=jc4VYzMAAAAJ:d1gkVwhDpl0C) <strong><span class='show_paper_citations' data='jc4VYzMAAAAJ:d1gkVwhDpl0C'></span></strong>

- THEMIS 是覆盖多任务、逾 4000 道题的综合基准，结合真实撤稿案例与逼真合成数据，系统评测 MLLM 在细粒度视觉造假推理上的能力。
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/aegis_overview.png' alt="AEGIS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AEGIS: A Holistic Benchmark for Evaluating Forensic Analysis of AI-Generated Academic Images](https://openreview.net/pdf?id=RW5pytG5nu)

Bo Zhang\*, **Tzu-Yen Ma\***, Zichen Tang, Junpeng Ding, Zirui Wang, Yizhuo Zhao, Peilin Gao, Zijie Xi, Zixin Ding, HaiyangSun, Haocheng Gao, Yuan Liu, Liangjia Wang, Yiling Huang, Yujie Wang, Yuyue Zhang, Ronghui Xi, Yuanze Li, Jiacheng Liu, Zhongjun Yang, Haihong E

- AEGIS 面向 AI 生成学术图像的专家级取证推理评测，强调领域复杂度、多样化伪造模拟与多维度取证指标。
</div>
</div>

# 🎖 获奖情况
{: #-honors-and-awards }
- *2025.04* 全国总冠军，第四届「梧桐杯」大数据创新大赛暨创客马拉松，中国移动。
  - AI生成内容泛滥的内容审核体系下，针对AI生成内容误识别率高、大规模审查易漏检，以及检测技术难落地三大痛点问题，提出了一种基于多模态大模型的内容审查解决方案。
- *2025.10* 三等奖（全校唯一名额）北京邮电大学港澳台侨研究生奖学金，北京邮电大学。
  - AI生成内容泛滥的内容审核体系下，针对AI生成内容误识别率高、大规模审查易漏检，以及检测技术难落地三大痛点问题，提出了一种基于多模态大模型的内容审查解决方案。

# 🛠 技术栈
{: #-skills }

- **编程语言:** Python, SQL, C
- **深度学习:** PyTorch, HuggingFace Transformers, vLLM
- **大模型技术:** 预训练/SFT 数据清洗、LoRA微调、提示词工程
- **多模态工具:** OpenCV, CLIP, Segment Anything (SAM)

# 💬 邀请报告
{: #-invited-talks }

- *2026.04*，AITIME 论道 · ICLR 2026 预讲会，北京邮电大学 BUPT ReasoningLab 专场。 \| [\[video\]](https://www.bilibili.com/video/BV12WoTBuETn/?spm_id_from=333.1387.collection.video_card.click)

<!-- # 💻 实习 {: #-internships } -->
