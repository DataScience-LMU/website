---
title: "News"
layout: textlay
excerpt: "Data Science @ LMU Munich"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }}</p> 
<em>{{ article.headline}}

{% endfor %}
