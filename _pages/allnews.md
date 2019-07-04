---
title: "News"
layout: textlay
excerpt: "Epigenome Technology Exploration Unit at RIKEN IMS."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
