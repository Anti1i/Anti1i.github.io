---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  dl {
    margin-bottom: 50px; /* 控制下方的间距 */
    clear: both;
    font-family: 'Arial', sans-serif; /* 更改字体为更现代的样式 */
  }

  dl dt img {
    width: 380px; /* 调整图片宽度 */
    height: 220px; /* 调整图片高度 */
    object-fit: cover; /* 确保图片按比例裁剪 */
    display: block;
    margin: 12px 12px 12px 0px; /* 调整图片的外边距 */
    
    /* 美化效果 */
    border-radius: 12px; /* 加强圆角效果 */
    border: 3px solid #e0e0e0; /* 使用较浅的边框颜色 */
    box-shadow: 4px 4px 12px rgba(0, 0, 0, 0.1); /* 添加更柔和的阴影效果 */
    padding: 6px; /* 增加内边距 */
    background-color: #fafafa; /* 更柔和的背景色 */
  }

  hr {
    border: 1px solid #f0f0f0; /* 使用更柔和的分隔线 */
    clear: both;
    margin-top: 15px; /* 增加顶部间距 */
    margin-bottom: 15px; /* 增加底部间距 */
  }

  dl dd {
    margin-top: 8px;
    margin-bottom: 8px;
    font-size: 1.1em; /* 调整字体大小使其更加突出 */
  }

  dl dd strong {
    font-weight: bold;
    color: #333; /* 使用深色文本 */
  }

  .co-first {
    color: #3c6ce7; /* 使用醒目的红色 */
  }

  .down {
    transform: rotate(180deg);
    transition: transform 0.3s ease; /* 增加平滑的旋转过渡效果 */
  }

  .down:hover {
    transform: rotate(0deg); /* 鼠标悬停时恢复原状 */
  }
</style>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, my name is Jingbo Wang (Chinese: 王靖博), an undergraduate student majoring in Information Security at the School of Cyber Science and Engineering, Wuhan University. I have the privilege of working with [Prof. Jing Chen](https://scholar.google.com/citations?hl=en&user=MZ8wtusAAAAJ) . 

My academic performance stands at [**GPA 3.89/4.0**](../images/transcript.png), with an [**Academic Rank of 4/106**](../images/rank.jpg) and a [**Comprehensive Rank of 1/106**](../images/comprehensive_rank_cert.pdf).

# 🔍 Research


My academic exploration focuses on AI Security, VR Privacy, and Federated Learning. Currently, my research is focused on:

* Federated Graph Learning & AI Fairness 🕸️
* Large Language Model (LLM) Security 🛡️
* VR Security & Side-Channel Attacks 🥽

# 🔥 News
* *2026.05*: Two papers were submitted to **NeurIPS 2026** and **UbiComp 2026** as the first author.
* *2025.11*: 🥉 Won the Bronze Medal in the **ARC Prize 2025** Global Challenge.
* *2025.09*: 🏆 Awarded the prestigious **Lei Jun Computer Scholarship**.
* *2025.05*: 🥇 Won the First Prize in the **Huawei ICT Competition** (National Final).

# 📝 Manuscripts / Preprints

### [1] BackSnoop: VR Visual Side-Channel Keystroke Inference via Rear-View Upper-Arm Kinematics
<div style="margin-bottom: 10px;">
  <span style="background-color: #f1f8ff; color: #0366d6; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 5px;">First Author</span>
  <span style="background-color: #fffbdd; color: #735c0f; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 10px;">Under Review at UbiComp 2026</span>
</div>

* **Research Focus**: VR Security, Visual Side-Channel Attacks, Keystroke Inference

<br>

### [2] E2Gen: Evidential Energy Generation Framework for Fair Federated Graph Learning
<div style="margin-bottom: 10px;">
  <span style="background-color: #f1f8ff; color: #0366d6; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 5px;">First Author</span>
  <span style="background-color: #fffbdd; color: #735c0f; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 10px;">Under Review at NeurIPS 2026</span>
</div>

* **Research Focus**: Federated Graph Learning, Fairness in AI, Energy-Based Models

<br>

### [3] Tackling LLM Instruction Conflicts via Energy-Driven Latent Conflict Detection
<div style="margin-bottom: 10px;">
  <span style="background-color: #f1f8ff; color: #0366d6; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 5px;">Co-author</span>
  <span style="background-color: #fffbdd; color: #735c0f; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 10px;">Under Review at IJCAI 2026</span>
</div>

* **Research Focus**: Large Language Models (LLMs), Instruction Tuning, Conflict Detection

<br>

### [4] CLICKID: Multimodal VR User Authentication via Click-Derived Hand Biometrics
<div style="margin-bottom: 10px;">
  <span style="background-color: #f1f8ff; color: #0366d6; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 5px;">Co-author</span>
  <span style="background-color: #fffbdd; color: #735c0f; padding: 2px 8px; border-radius: 4px; font-size: 13px; font-weight: bold; margin-right: 10px;">Under Review at MobiCom 2026</span>
</div>

* **Research Focus**: VR Authentication, Hand Biometrics, Multimodal Security

# 🎖 Scholarships and Honors
* **Bronze Medal**, ARC Prize Global Challenge [<a href="../images/kaggle.png" target="_blank">Certificate</a>] [2025]
* **National First Prize**, Huawei ICT Competition [<a href="../images/Huawei.png" target="_blank">Certificate</a>] [2025]
* **National Second Prize**, DataCon Big Data Security Analysis Competition [<a href="../images/datacon.jpeg" target="_blank">Certificate</a>] [2025]
* **National Second Prize**, MathorCup Big Data Competition [<a href="../images/mathor.pdf" target="_blank">Certificate</a>] [2024]
* **Lei Jun Computer Scholarship**, Wuhan University [<a href="../images/leijun.pdf" target="_blank">Certificate</a>] [2024-2025]
* **First-Class Scholarship**, Wuhan University [<a href="../images/first.pdf" target="_blank">Certificate</a>] [2024-2025]

<hr>


# 📖 Education

**2023.09 - Present**
*Undergraduate*, School of Cyber Science and Engineering, Wuhan University
* Major: Information Security
* **GPA: 3.89 / 4.0**
* **Rankings: 4 / 106 (Academic) \| 1 / 106 (Comprehensive)**


<br/>






