---
layout: archive
title: Articles
date: 2016-01-15
modified:
excerpt: Articles I wrote
image:
  feature:
  teaser:
  thumb:
permalink: /articles/
---

<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
