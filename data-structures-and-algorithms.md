---
layout: page
title: Data Structures & Algorithms
permalink: /data-structures-and-algorithms/
---

{% for item in site.data-structures-and-algorithms %}
<h2><a href="{{ item.url }}">{{ item.title }}</a></h2>
  <p>{{ item.excerpt }}</p>
{% endfor %}