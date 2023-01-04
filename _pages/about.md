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
I obtained my B.E. degree of Information Security from Harbin Institute of Technology (HIT) in 2012. And during college, I was exchanged to Feng Chia University (Taiwan) in 2010.
I obtained my Ph.D. degree of Computer Applications Technology from the <a href="http://tca.iscas.ac.cn/">TCA lab</a> at <a href="http://english.is.cas.cn/"> Institute of Software Chinese Academy of Sciences (ISCAS) </a> in 2012-2018,
was co-advised by Professor <a href="https://dblp.org/pers/hd/s/Su:Purui"> Purui Su </a> and Professor <a href="https://dblp.uni-trier.de/pers/hd/f/Feng:Dengguo"> Dengguo Feng </a>. After, I worked as a Postdoc at the <a href="https://plato.ist.psu.edu/">Software Systems Security lab</a> headed by Professor <a href="https://faculty.ist.psu.edu/wu/">Dinghao Wu</a> in The Pennsylvania State University (PSU) in 2018-2019.<br>

<p>
My research interests focus on <b> software security</b>, including <b>program analysis</b>, <b>vulnerability analysis</b> and <b>malware detection</b>.
I am now working on fuzzing, program analysis and vulnerability exploitation. There are several projects including: 
</p>
<div>
<ul>                  
<li><b>Vulnerability discovery/detection/assessment</b></li>
<li><b>Patch analysis and software supply chain security</b></li>
</ul>
</div>


<!--# 🔥 News
- *2022.02*: &nbsp;🎉 -->

# 📝 Publications 

<!-- 2022 --> 
- [Understanding and Mitigating Label Bias in Malware Classification: An Empirical Study](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Jia Yan, **Xiangkun Jia**, Lingyun Ying, Jia Yan, Purui Su<br>
The 22nd IEEE International Conference on Software Quality, Reliability and Security (<b>QRS 2022</b>)<br>

- [DitDetector: Bimodal Learning based on Deceptive Image and Text for Macro Malware Detection](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Jia Yan, Ming Wan, **Xiangkun Jia**, Lingyun Ying, Purui Su, Zhanyi Wang<br>
The Annual Computer Security Applications Conference (<b>ACSAC 2022</b>)<br>

- [HTFuzz: Heap Operation Sequence Sensitive Fuzzing](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Yuanping Yu, **Xiangkun Jia***, Yuwei Liu, Yanhao Wang, Qian Sang, Chao Zhang, Purui Su<br>
The 38th IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2022</b>)<br>
The code is released at <b>https://github.com/sharedata21/HTFuzz</b><br>

- [Automatic exploitation generation method of write-what-where vulnerability](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Huafeng Huang, Purui Su, Yi Yang, **Xiangkun Jia**<br>
<b>Journal on Communications.</b> Vol. 43 No. 1, 2022. (in Chinese)<br>
<!-- 2022 --> 

<!-- 2021 -->
- [InstruGuard: Find and Fix Instrumentation Errors for Coverage-based Greybox Fuzzing](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Yuwei Liu, Yanhao Wang, Purui Su, Yuanping Yu, **Xiangkun Jia***<br>
The 37th IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2021</b>)<br>
The code is released at <b>https://github.com/Marsman1996/instruguard</b><br>

<!-- 2021 -->

<!-- 2020 --> 
- [Not All Coverage Measurements Are Equal: Fuzzing by Coverage Accounting for Input Prioritization](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Yanhao Wang, **Xiangkun Jia**, Yuwei Liu, Kyle Zeng, Tiffany Bao, Dinghao Wu, Purui Su<br>
The Network and Distributed System Security Symposium (<b>NDSS 2020</b>)<br>
The code is released at <b>https://github.com/TortoiseFuzz/TortoiseFuzz</b><br>
<!-- 2020 --> 

<!-- phd --> 
- [Towards Efficient Heap Overflow Discovery](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
**Xiangkun Jia**, Chao Zhang, Purui Su, Yi Yang, Huafeng Huang, Dengguo Feng<br>
Proceedings of the 26th USENIX Security Symposium (<b>Security 2017</b>)<br>

- [Automatically assessing crashes from heap overflows](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
Liang He, Yan Cai, Hong Hu, Purui Su, Zhenkai Liang, Yi Yang, Huafeng Huang, Jia Yan, **Xiangkun Jia**, Dengguo Feng<br>
The 32nd IEEE/ACM International Conference on Automated Software Engineering (<b>ASE 2017</b>)<br>

- [Safety analysis and evaluation of security protocol implementation](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)<br>
**Xiangkun Jia**, Jia Yan, Purui Su<br>
<b>Bulletin of Chinese Association for Cryptologic Research.</b> Issue 6, 2014. (in Chinese)<br>
<!-- phd --> 

# 🎖 Honors and Awards
- The First Prize of "ZongHengBei" RHG AUTOPWN
- The Third Prize of BCTF AUTOPWN (20200807) founded by Baidu
- Internet security scholarship of CHINA internet development foundation in 2017
- National Scholarship in 2017
- Excellent graduate of Heilongjiang Province in China in 2012


# 💻 Professional Activities
- Student PC for IEEE Symposium on Security and Privacy (Oakland), 2018
- Sub-reviewer for Conferences including AsiaCCS'2021, ICICS'2021, ICICS'2020, CCS'2019, CNS'2019, CSET'17, RAID'17, VARA'17, CODASPY'16
- Sub-reviewer for Journals including IEEE Transactions on Network and Service Management, Transactions on Software Engineering, Chinese Journal of Computers, Journal of Software, Chinese Journal of Electronics