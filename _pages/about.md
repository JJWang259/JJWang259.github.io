---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher in the Department of Animal Science at North Carolina State University, working with [Dr. Jicai Jiang](https://cals.ncsu.edu/animal-science/people/jicai-jiang). My research focuses on developing and applying statistical genomics methods for livestock populations, with particular emphasis on cattle and pig genetics.

## Research Interests

My work centers on adapting and developing fine-mapping and rare variant analysis methods for farm animal populations. These populations present unique analytical challenges compared to human genetics, including extensive genetic relatedness and strong linkage disequilibrium patterns. I am particularly interested in:

- Statistical fine-mapping methods for livestock (BFMAP-SSS, FINEMAP-adj, SuSiE-adj)
- Rare variant association analysis
- Genomic prediction and quantitative trait locus (QTL) mapping
- Computational methods for large-scale genomic data analysis


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

