---
title: "News"
layout: textlay
excerpt: "Blackman Lab at The University of California, Berkeley"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify | remove: "<p>" | remove: "</p>" }}</p>
{% endfor %}

<p> &nbsp; </p>
