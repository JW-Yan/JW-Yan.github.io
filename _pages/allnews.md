---
title: "News"
layout: textlay
excerpt: "Jingwen Lab at IUI."
sitemap: false
permalink: /allnews.html
---

# All news

{% for article in site.data.news %}
<p> 
  {{ article.date }} 
  {{ article.headline}} <br/>
</p>
{% endfor %}
