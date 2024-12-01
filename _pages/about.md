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

## Bio
Xiyue Zhang (<em>Pronounced: Shee-you-eh Jahng</em>) is a Lecturer (US equiv. Assistant Professor) in the [School of Computer Science](https://www.bristol.ac.uk/engineering/schools/computer-science/) at the [University of Bristol](https://www.bristol.ac.uk/).
Her current research mainly focuses on trustworthy deep learning, formal modelling and verification.
Previously, she was a postdoctoral research associate working with [Prof. Marta Kwiatkowska](https://www.cs.ox.ac.uk/people/marta.kwiatkowska/) in the Department of Computer Science at the [University of Oxford](https://www.cs.ox.ac.uk/) (2022-2024).
She received her Ph.D. (2022) in Applied Mathematics, advised by [Prof. Meng Sun](https://www.math.pku.edu.cn/teachers/sunm/indexen.html), and her B.Sc. (2017) in Information and Computing Science from School of Mathematical Sciences, [Peking University](https://english.pku.edu.cn/).


<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

## Recruitment
I am looking for motivated Ph.D. students with a strong interest in formal verification or empirical analysis of data-driven models and systems. Ideal candidates will have a background in computer science or a closely related field. Scholarships are available for both home and international students, including those at the University-level, Faculty-level, CDTs, CSC, and others. Feel free to email me if you'd like to discuss further!

# 🔥 News
- *2024.11*: &nbsp;🎉🎉 I am honoured to present an inaugural talk on Neural Network Certification to kick off the Trustworthy Systems Lab (TSL) seminar series at the University of Bristol.
Join our [Teams channel](https://teams.microsoft.com/l/channel/19%3a22010dd992a94c4fad51ebbe0e678fc5%40thread.tacv2/General?groupId=7c8a30f5-2218-4763-9fa3-7ee3d23ab033&tenantId=b2e47f30-cd7d-4a4e-a5da-b18cf1a4151b) for more details.
This is an open group, so feel free to spread the word! To observe, participate in debates, or present, please reach out. Join our mailing list for weekly invitations and updates on future talks.
- *2024.08*: &nbsp;🎉🎉 Our paper "FAST: Boosting Uncertainty-based Test Prioritization Methods for Neural Networks via Feature Selection" is accpeted by [ASE 2024](https://conf.researchr.org/home/ase-2024).
- *2024.07*: I give a talk at [SAIV 2024](https://www.aiverification.org/) speaking on preimage approximation-based neural network analysis.
- *2024.05*: &nbsp;🎉🎉 Our paper "Automated Design of Linear Bounding Functions for Sigmoidal Nonlinearities in Neural Networks" is accpeted by [ECML PKDD 2024](https://ecmlpkdd.org/2024/).
- *2024.05*: I present my work on neural network certification at [Oxbridge Women in Computer Science Conference 2024](https://www.cs.ox.ac.uk/conferences/Oxbridge2024/index.html).
- *2024.04*: I am going to give a talk at [TACAS 2024](https://etaps.org/2024/conferences/tacas/) speaking on Preimage Approximation (Backward Analysis) for Neural Networks. See you in Luxembourg!
- *2023.12*: &nbsp;🎉🎉 Our paper "Provable Preimage Under-Approximation for Neural Networks" is accpeted by [TACAS 2024](https://link.springer.com/chapter/10.1007/978-3-031-57256-2_1).
- *2023.10*: &nbsp;🎉🎉 I am selected as a [DAAD AInet fellow](https://www.daad.de/en/the-daad/postdocnet/details-and-application/) for the Postdoc-NeT-AI 11/2023.
- *2023.08*: &nbsp;🎉🎉 Our paper "Weighted Automata Extraction and Explanation of Recurrent Neural Networks for Natural Language Tasks" is accpeted by Journal of Logical and Algebraic Methods in Programming.
- *2023.08*: &nbsp;🎉🎉 Our paper "When to Trust AI: Advances and Challenges for Certification of Neural Networks" is accepted by FedCSIS 2023.
- *2023.08*: &nbsp;🎉🎉 I am selected as [Future Digileader '23](https://www.digitalfutures.kth.se/news/future-digileaders-23/) by [Digital Futures](https://www.digitalfutures.kth.se/).
- *2023.04*: &nbsp;🎉🎉 Our paper "Using Z3 for Formal Modeling and Verification of FNN Global Robustness" is accpeted by SEKE 2023.
- *2022.12*: &nbsp;🎉🎉 Our paper "kProp: Multi-Neuron Relaxation Method for Neural Network Robustness Verification" is accpeted by FSEN 2023.
- *2022.10*: I will serve on the Program Committee of [TASE’23](https://bristolpl.github.io/tase2023/), to be held in Bristol, UK, on 04-06 July 2023. Welcome submissions!
- *2022.09*: I give a talk at the [ICTAC 2022 conference](http://viam.science.tsu.ge/clas2022/) speaking on A Unifying Logical Framework for Neural Networks.
<!-- - *2022.08*: &nbsp;🎉🎉 Our paper "Towards a Unifying Logical Framework for Neural Networks" is accepted by ICTAC 2022.
- *2022.06*: &nbsp;🎉🎉 Our paper "Extracting Weighted Finite Automata from Recurrent Neural Networks for Natural Languages" is accpeted by ICFEM 2022. -->



# 📝 Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

## [FAST: Boosting Uncertainty-based Test Prioritization Methods for Neural Networks via Feature Selection](https://dl.acm.org/doi/abs/10.1145/3691620.3695472) (ASE 2024)
Jialuo Chen, Jingyi Wang, **Xiyue Zhang**, Youcheng Sun, Marta Kwiatkowska, Jiming Chen, Peng Cheng
[[arxiv](https://arxiv.org/pdf/2409.09130)] [[code](https://github.com/Testing4AI/FAST)]



# 🏫 Teaching
## Undergraduate Supervision
- *2024.10-2025.05* Nikolas Willems (MEng-CS and Math)
- *2025.01-2025.05* Xiqi Zheng (MEng-CS)

## Teaching Units
- *TB1 2024-25* Programming in C (Project Assesement)

# 🎖 Honors and Awards
- *2023.10* DAAD AInet fellow for the Postdoc-NeT-AI 
- *2023.08* Future Digileaders Award 2023 (by Digital Futures for early-career researchers)
- *2022.06* Doctoral Dissertation Award of Peking University 
- *2020&2021.10* National Scholarship (Highest-level scholarship 0.1%)

# 📖 Education
- *2017.09 - 2022.06*, PhD in Applied Mathematics, School of Mathematical Sciences, Peking University.
- *2019.02 - 2020.03*, Research Assistant, School of Computer Science & Engineering, Nanyang Technological University.
- *2017.08*: Visiting Student, Singapore University of Technology and Design.
- *2013.09 - 2017.06*, BSc in Information and Computing Science, School of Mathematical Sciences, Peking University.

# 💬 Invited Talks
- *2024.11*, Inaugural talk on Neural Network Certification hosted at the Trustworthy Systems Lab (TSL) seminar series.
- *2024.04*, Recent Advances in Neural Network Certification, Seminar talk at CISPA Helmholtz Center for Information Security.
- *2023.07*, Preimage Approximation for Neural Networks and Beyond, Seminar talk at School of Mathematical Scienes, Peking University.