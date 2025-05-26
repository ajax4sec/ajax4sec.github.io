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
I obtained my B.E. degree in Information Security from Harbin Institute of Technology (HIT) in 2012. During college, I was transferred to Feng Chia University (Taiwan) in 2010.
I obtained my Ph.D. degree from the TCA lab at <a href="http://english.is.cas.cn/"> Institute of Software Chinese Academy of Sciences (ISCAS) </a> in 2012-2018,
was co-advised by Professor <a href="https://people.ucas.ac.cn/~purui"> Purui Su </a> and Professor <a href="https://casad.cas.cn/ysxx2022/ysmd/xxjs/201911/t20191121_4724697.html"> Dengguo Feng </a>. After, I worked as a Postdoc at the Software Systems Security lab headed by Professor <a href="https://faculty.ist.psu.edu/wu/">Dinghao Wu</a> in The Pennsylvania State University (PSU) in 2018-2019.<br>

<p>
My research interests focus on <b> software engineering and software security</b>, including <b>program analysis</b>, <b>vulnerability analysis</b> and <b>malware detection</b>.
I am now working on several projects, including: 
</p>
<div>
<ul>
<li><b>Dynamic program analysis</b></li>                  
<li><b>Vulnerability discovery based on fuzzing</b></li>
<li><b>Patch analysis and software supply chain security</b></li>
</ul>
</div>


<!--# 🔥 News
- *2022.02*: &nbsp;🎉 -->

# 📝 Publications 

<!-- 2025 -->
- Towards Efficient C/C++ Vulnerability Impact Assessment in Package Management Systems.[]()<br>
Zibo Wang, **Xiangkun Jia**, Jia Yan, Yi Yang, Huafeng Huang, Purui Su<br>
The 27th International Conference on Information and Communications Security (<b>ICICS 2025, CCF-C</b>)<br>

<!-- 2024 -->
- AirTaint: Making Dynamic Taint Analysis Faster and Easier.[]()<br>
Qian Sang, Yanhao Wang, Yuwei Liu, **Xiangkun Jia***, Tiffany Bao, Purui Su<br>
The 45th IEEE Symposium on Security and Privacy (<b>S&amp;P 2024, CCF-A</b>)<br>

- AFGen: Whole-Function Fuzzing for Applications and Libraries.[]()<br>
Yuwei Liu, Yanhao Wang, **Xiangkun Jia**, Zheng Zhang, Purui Su<br>
The 45th IEEE Symposium on Security and Privacy (<b>S&amp;P 2024, CCF-A</b>)<be>

<!-- 2023 -->
- LGBRoot: Local Graph-Based Automated Vulnerability Root Causes Analysis.[📃]()<br>
Yuanping Yu, Purui Su, Huafeng Huang, **Xiangkun Jia**<br>
<b>Journal of Software.</b> (CCF-T1, in Chinese)<br>

- A fine-grained assessment method of vulnerability impact scope for PyPI ecosystem.[]()<br>
Zibo Wang, **Xiangkun Jia***, Lingyun Ying, Purui Su<br>
<b>Journal of Software.</b> (CCF-T1, in Chinese)<br>

- Research Progress and Trends in Software Supply Chain Security.[📂Online](https://dl.ccf.org.cn/article/detail.html?_ack=1&id=6476813273516032)<br>
**Xiangkun Jia**, Yuan Zhang, Jia Yan, Purui Su, Min Yang, Dengguo Feng<br>
<b>2021-2022 China Computer Science and Technology Development Report.</b> (in Chinese)<br>

<!-- 2022 --> 
- Understanding and Mitigating Label Bias in Malware Classification: An Empirical Study.[]()<br>
Jia Yan, **Xiangkun Jia***, Lingyun Ying, Jia Yan, Purui Su<br>
The 22nd IEEE International Conference on Software Quality, Reliability and Security (<b>QRS 2022, CCF-C</b>)<br>

- DitDetector: Bimodal Learning based on Deceptive Image and Text for Macro Malware Detection.[📂Code](https://github.com/TCA-ISCAS/DitDetector)<br>
Jia Yan, Ming Wan, **Xiangkun Jia**, Lingyun Ying, Purui Su, Zhanyi Wang<br>
The Annual Computer Security Applications Conference (<b>ACSAC 2022, CCF-B</b>)<br>

- HTFuzz: Heap Operation Sequence Sensitive Fuzzing.[📂Code](https://github.com/TCA-ISCAS/HTFuzz)<br>
Yuanping Yu, **Xiangkun Jia***, Yuwei Liu, Yanhao Wang, Qian Sang, Chao Zhang, Purui Su<br>
The 38th IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2022, CCF-A</b>)<br>


- Automatic exploitation generation method of write-what-where vulnerability.<br>
Huafeng Huang, Purui Su, Yi Yang, **Xiangkun Jia**<br>
<b>Journal on Communications.</b> Vol. 43 No. 1, 2022. (CCF-T1, in Chinese)<br>
<!-- 2022 --> 

<!-- 2021 -->
- InstruGuard: Find and Fix Instrumentation Errors for Coverage-based Greybox Fuzzing.[📂Code](https://github.com/TCA-ISCAS/InstruGuard)<br>
Yuwei Liu, Yanhao Wang, Purui Su, Yuanping Yu, **Xiangkun Jia***<br>
The 37th IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2021, CCF-A</b>)<br>

<!-- 2021 -->

<!-- 2020 --> 
- Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization.[📂Code](https://github.com/TCA-ISCAS/TortoiseFuzz)<br>
Yanhao Wang, **Xiangkun Jia**, Yuwei Liu, Kyle Zeng, Tiffany Bao, Dinghao Wu, Purui Su<br>
The Network and Distributed System Security Symposium (<b>NDSS 2020, CCF-A</b>)<br>
<!-- 2020 --> 

<!-- phd --> 
- Towards Efficient Heap Overflow Discovery.<br>
**Xiangkun Jia**, Chao Zhang, Purui Su, Yi Yang, Huafeng Huang, Dengguo Feng<br>
Proceedings of the 26th USENIX Security Symposium (<b>Security 2017, CCF-A</b>)<br>

- Automatically assessing crashes from heap overflows.<br>
Liang He, Yan Cai, Hong Hu, Purui Su, Zhenkai Liang, Yi Yang, Huafeng Huang, Jia Yan, **Xiangkun Jia**, Dengguo Feng<br>
The 32nd IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2017, CCF-A</b>)<br>

- Safety analysis and evaluation of security protocol implementation.<br>
**Xiangkun Jia**, Jia Yan, Purui Su<br>
<b>Bulletin of Chinese Association for Cryptologic Research.</b> Issue 6, 2014. (in Chinese)<br>
<!-- phd --> 

# 🏆 Honors and Awards
- Supported by Youth Innovation Promotion Association CAS
- Supported by the Outstanding Science and Technology Talent Program of ISCAS
- The First Prize of "ZongHengBei" RHG AUTOPWN
- The Third Prize of BCTF AUTOPWN (20200807), founded by Baidu
- Internet security scholarship of CHINA Internet Development Foundation in 2017
- National Scholarship in 2017
- Excellent graduate of Heilongjiang Province in China in 2012


# 💻 Professional Activities
- PC for Conferences including CCS 2025, FUZZING 2025, FC 2025, AsiaCCS 2025, USENIX Security 2024, CCS 2024, ASE 2024, SANER 2024
- Sub-reviewer/Student PC for Conferences including SecureComm'2023, ACNS'2023, AsiaCCS'2021, ICICS'2021, ICICS'2020, CCS'2019, CNS'2019, S&P 2018, CSET'17, RAID'17, VARA'17, CODASPY'16
- Youth Editor for the Chinese Journal of Network and Information Security, Chinese Journal of Cyber Security
- Reviewer for Journals including IEEE Transactions on Information Forensics & Security, IEEE Transactions on Network and Service Management, Transactions on Software Engineering, Chinese Journal of Computers, Journal of Software, Chinese Journal of Electronics
