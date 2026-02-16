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

I am **Zhipei Xu (徐志沛)**, a second-year Master's student at the <a href='https://www.ece.pku.edu.cn/'>School of Electronic and Computer Engineering</a>, <a href='https://english.pku.edu.cn/'><img src="images/pku.png" style='width: 1.2em; vertical-align: sub;'> Peking University</a>, advised by <a href='https://jianzhang.tech/'>Prof. Jian Zhang</a>. Previously, I received my B.Eng degree from the <a href='https://www2.scut.edu.cn/ee/'>School of Electronic and Information Engineering</a>, <a href='https://www.scut.edu.cn/new/'><img src="images/scut.png" style='width: 1.2em; vertical-align: sub;'> South China University of Technology</a>. Please feel free to reach out via email (zhipeixu@stu.pku.edu.cn).

My research focuses on **Trustworthy Multi-modal AI**, with specific interests in **Multi-modal Large Language Models**, **Image/Video Forgery Detection**, and **AIGC Security**. I have published multiple papers at top-tier venues including CVPR, ICLR, NeurIPS, and ACM MM, with works spanning explainable forgery localization, multi-agent detection frameworks, and robust watermarking/steganography for copyright protection. For more details on my publications, please visit my profiles on [Google Scholar](https://scholar.google.com/citations?user=504N5M0AAAAJ&hl=en) (<a href='https://scholar.google.com/citations?user=504N5M0AAAAJ&hl=en'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fzhipeixu%2Fzhipeixu.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations" style="vertical-align: middle;"></a>).

# 🔥 News
- *2025.08.02:* &nbsp;🎉🎉 Gaussianseal has been accepted by **MIR**!
- *2025.02.27:* &nbsp;🎉🎉 OmniGuard have been accepted by **CVPR** 2025!
- *2025.01.23:* &nbsp;🎉🎉 FakeShield and SecureGS has been accepted by **ICLR** 2025!


<details>
<summary>Old News</summary>
<ul>
  <li>2024.09.25: &nbsp;🎉🎉 GS-hider has been accepted by <strong>NeurIPS</strong> 2024!</li>
  <li>2024.07.05: &nbsp;🎉🎉 V2A-Mark has been accepted by <strong>ACM MM</strong> 2024! </li>
</ul>
</details>


# 📝 Selected Publications 

(\* Equal contribution, † Project Leader, ‡ Corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/fakeshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FakeShield: Explainable Image Forgery Detection and Localization via Multi-modal Large Language Models](https://openreview.net/pdf?id=pAQzEY7M03) \\
**Zhipei Xu**, Xuanyu Zhang, Runyi Li, Zecheng Tang, Qing Huang, Jian Zhang \\
*International Conference on Learning Representations (ICLR)*, 2025

[**Project Page**](https://zhipeixu.github.io/projects/FakeShield/) | [**Data & Code** ![](https://img.shields.io/github/stars/zhipeixu/FakeShield?style=social)](https://github.com/zhipeixu/FakeShield) <strong><span class='show_paper_citations' data='504N5M0AAAAJ:f2IySw72cVMC'></span></strong>
- We propose the explainable IFDL task and design FakeShield, a multi-modal framework capable of evaluating image authenticity, generating tampered region masks, and providing a judgment basis based on pixel-level and image-level tampering clues.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/AvatarShield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AvatarShield: Visual Reinforcement Learning for Human-Centric Synthetic Video Detection](https://arxiv.org/pdf/2505.15173) \\
**Zhipei Xu**, Xuanyu Zhang, Qing Huang, Xing Zhou, Jian Zhang \\
*Under Review*

- We focus on pose, audio, and text-driven human video forgery and propose the first human-centered video forgery dataset, FakeHumanVid, along with the first reinforcement learning-based human video forgery detection framework, AvatarShield.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/UniShield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UniShield: An Adaptive Multi-Agent Framework for Unified Forgery Image Detection and Localization](https://arxiv.org/pdf/2510.03161) \\
Qing Huang\*, **Zhipei Xu\***, Xuanyu Zhang, Xiangyu Yu, Jian Zhang \\
*Under Review*

- We propose the first multi-agent framework, UniShield, designed to address image forgery detection tasks. It efficiently utilizes a Perception Agent and a Detection Agent to call upon various expert detectors, enabling unified image forgery detection, including DeepFake, AIGC, image forgery, and document forgery.
</div>
</div>




# 🎖 Selected Honors and Awards
- *2023.10* National Scholarship.
- *2023.10* National College Student Mathematical Modeling Competition - Provincial First Prize.
- *2022.10* National Scholarship.
- *2021.10* Samsung Scholarship.


# 📖 Educations
- *2024.09 - 2027.06 (expected)*, MSc., Computer Science and Technology, Peking University.
- *2020.09 - 2024.06*, B.S., Communication Engineering, South China University of Technology.

# 💬 Services
- Conference Reviewer for ICLR, ICML, NeurIPS, ECCV, ICCV, ACM MM.
- Journal Reviewer for IEEE TIP, IEEE TCSVT, VCIP.


