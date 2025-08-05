---
layout: default
title: "Ming Chu — Healthcare IT & Machine Learning"
description: "Healthcare IT & machine-learning professional blending frontline support with data-driven innovation to improve patient care."
permalink: /
---

## 🧠 Professional Summary

I bridge **front-line healthcare IT** with **predictive analytics**, turning raw data into actionable insight that reduces downtime and elevates patient-care quality.  
My work integrates **Epic EHR support**, **cloud computing**, and **machine learning** to improve healthcare operations and patient outcomes.

---

## 🎓 Education

<table style="width:100%">
  <tr>
    <td><strong>M.S. Computer Science (Big Data Analysis)</strong> — <em>Florida Atlantic University, 2024</em></td>
    <td style="text-align:right;">GPA 4.0/4.0</td>
  </tr>
  <tr>
    <td><strong>B.A. Computer Science (Applied Mathematics)</strong> — <em>Florida International University, 2020</em></td>
    <td style="text-align:right;">UPE Honor Society</td>
  </tr>
</table>

---

## 🛠️ Core Skills

| **Category**             | **Stack / Tools**                                   |
|--------------------------|-----------------------------------------------------|
| Languages                | Python · SQL · JavaScript                            |
| ML / Data                | Pandas · NumPy · scikit-learn · TensorFlow · PyTorch · OpenCV |
| Cloud / DevOps           | Azure ML · Git · Jupyter · Jira                      |
| Healthcare IT / EMR      | Epic EHR support · Technical troubleshooting         |
| Other                    | Scientific writing · Public speaking · Team collaboration |

---

## 💼 Selected Projects

### Driver Behavior Detection System  
Developed a CNN + BiLSTM pipeline (**99.1 % accuracy**) to detect driver distraction and drowsiness in real time using **OpenCV**.  
[*Journal of Big Data* (2024)](https://doi.org/10.1186/s40537-024-00890-0)

### AI Stock Sentiment Analysis  
Built a **real-time Twitter sentiment pipeline** (RNN/LSTM) achieving **85 % bullish-signal precision** with live push alerts.

### Healthcare IT Service Desk  
Resolved 100+ weekly Epic/IT tickets and authored 30+ KB docs in Jira, **reducing resolution time by 30 %**.

---

## 📚 Publications

- **“Comprehensive Study of Driver Behavior Monitoring Systems”** — *Journal of Big Data, 2024* [[DOI]](https://doi.org/10.1186/s40537-024-00890-0)

---

## 🧾 Certifications

- Microsoft **Azure Fundamentals (AZ-900)** (2025)  
- Graduate Certificate **Big Data Analytics** (2024)  
- IBM **Machine Learning Specialist – Associate** (2022)  
- Microsoft **Azure Data Scientist (DP-100)** *(in progress)*  
- Google **Professional Machine Learning Engineer (MLE)** *(planned)*

---

## 🏆 Honors

- 🥉 *3-Minute Thesis* — 2nd Runner-Up, FAU (2024)  
- 🎓 **UPE Honor Society** — FIU

---

## ✍️ Latest Posts

<ul>
  {% for post in site.posts limit:3 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> <small>– {{ post.date | date: "%B %d, %Y" }}</small></li>
  {% endfor %}
</ul>

---

*Site built with Jekyll & hosted on GitHub Pages.*  
© {{ "now" | date: "%Y" }} Ming Chu
