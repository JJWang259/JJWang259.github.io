---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% assign newsItems = site.data.news | sort: 'date' | reverse %}
{% for news in newsItems %}
  <p>
    <strong>{{ news.date | date: "%B %Y" }}</strong><br>
    {{ news.title | markdownify | remove: '<p>' | remove: '</p>' }}
  </p>
{% endfor %}
