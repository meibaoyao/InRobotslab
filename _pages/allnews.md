---
title: "News"
layout: textlay
excerpt: "CVIR Lab at changchun university of science and technology."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
