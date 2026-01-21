---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher in the Department of Animal Science at North Carolina State University working with [Dr. Christian Maltecca](https://cals.ncsu.edu/animal-science/people/christian-maltecca/) and [Dr. Jicai Jiang](https://cals.ncsu.edu/animal-science/people/jicai-jiang/). Previously, I obtained my Ph.D. in Animal Science (Quantitative Genetics) and M.S. in Statistics from NC State University under the supervision of Dr. Jicai Jiang.

My research focuses on statistical and computational methods for genomics. During my PhD, I investigated approaches for genomic prediction using deep learning, GWAS, fine-mapping, functional enrichment analysis, and heritability partitioning in farm animals characterized by extensive genetic relatedness and strong linkage disequilibrium. My current work focuses on rare variant association analysis in farm animal populations to characterize the role of rare variants in complex traits.


## Education

**Ph.D. in Animal Science**  
North Carolina State University (2021-2025)  

**M.S. in Statistics**  
North Carolina State University (2022-2025)

**M.S. in Animal Breeding and Genetics**  
China Agricultural University (2018-2021)

**B.S. in Animal Science**  
China Agricultural University (2014-2018)

## &#x1F4F0; Latest News ([See All](/news/))

<div style="text-align:justify">
{% assign newsItems = site.data.news | sort: 'date' | reverse %}
{% for news in newsItems limit:5 %}
  <p>
    <strong>{{ news.date | date: "%b %Y" }}</strong>: 
    {{ news.title | markdownify | remove: '<p>' | remove: '</p>' }}
  </p>
{% endfor %}
</div>

---

<p style="font-size: 0.85em; text-align: center;">255 Polk Hall, 120 W Broughton Dr, NC State University, Raleigh, NC, 27606, USA</p>

