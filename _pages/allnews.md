---
title: "News"
layout: textlay
excerpt: "QFQT Lab at NIT Patna."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
