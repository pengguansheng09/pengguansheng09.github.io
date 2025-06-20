---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)] | [[DBLP](https://dblp.org/pid/19/2969-1.html)] | [[View by topic](https://jd92.wang/research/)]

#### Publication list

Guansheng Peng, Jianjiang Wang, Guopeng Song, Aldy Gunawan, Lining Xing and Pieter Vansteenwegen. "Branch-and-Cut-and-Price for Agile Earth Observation Satellite Scheduling". European Journal of Operational Research, 2025. (CAS:Q2, Top, JCR:Q1, IF:6) (Working paper, Major revision).\\

Guansheng Peng}. Learning-augmented Ng-path Relaxation for Vehicle Routing Problem with Time Windows. 2025. (Working paper).\\

Guansheng Peng, Guopeng Song, Lining Xing, Aldy Gunawan and Pieter Vansteenwegen. "An Exact Algorithm for Agile Earth Observation Satellite Scheduling with Time-Dependent Profits", Computers \& Operations Research, 2020. 120:104946. (CAS:Q2, JCR:Q1, IF:4.1) \\

Guansheng Peng, Guopeng Song, Yongming He, Jing Yu, Shang Xiang, Lining Xing, Pieter Vansteenwegen. "Solving the Agile Earth Observation Satellite Scheduling Problem with Time-Dependent Transition Times". IEEE Transactions on Systems Man Cybernetics:Systems, 2020. (CAS:Q1, JCR:Q1, IF:8.8)\\

Guansheng Peng, Reginald Dewil, Cédric Verbeeck, Aldy Gunawan, Lining Xing, Pieter Vansteenwegen. "Agile Earth Observation Satellite Scheduling: an Orienteering Problem with Time-Dependent Profits and Travel Times". Computers \& Operations Research, 2019, 111:84-98. (CAS:Q2, JCR:Q1, IF:4.1)\\

Guansheng Peng, Suoyi Tan, Jun Wu, Holme Petter. "Trade-offs between Robustness and Small-world Effect in Complex Networks". Scientific Reports, 2016, 6:37317. (CAS:Q2, JCR:Q1, IF:3.8) \\

Guansheng Peng, Jun Wu. "Optimal network topology for structural robustness based on natural connectivity". Physica A, vol.443, pp. 212-220, 2015. (CAS:Q3, JCR:Q2, IF:2.8) \\

Jiaojiao Li, Jianghan Zhu, Guansheng Peng, Jianjiang Wang, Lu Zhen, Erik Demeulemeester, "Branch-Price-and-Cut algorithms for the team orienteering problem with interval-varying profits". European Journal of Operational Research, 2024. 319(3):793-807. \\

Ke Wang, Guansheng Peng, and Jun Wu. "Analyzing Vulnerability of Optical Fiber Network Considering Recoverability". Reliability Engineering \& System Safety, 2022. 221:108308. \\

 Jiawei Zhang, Lining Xing, Guansheng Peng, Feng Yao, Cheng Chen. "A large-scale Multi-objective Satellite Data Transmission Scheduling Algorithm based on SVM+NSGA-II". Swarm and Evolutionary Computation, 2019, 50:100560. \\

Shang Xiang, Lining Xing, Ling Wang, Yongquan Zhou, and Guansheng Peng. "Enhanced pigeon inspired optimisation approach for Agile Earth observation satellite scheduling". International Journal of Bio-Inspired Computation, 2021, 17(3):131-141.



> #### Books
> 
> <div class="publications">
> 
> {% for y in page.years %}
>   {% bibliography -f books -q @*[year={{y}}]* %}
> {% endfor %}
> 
> </div>

#### Papers

<div class="publications">

{% for y in page.years %}
<div>{{y}}</div>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
