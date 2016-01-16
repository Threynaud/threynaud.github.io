---
layout: archive
title: Portfolio
date: 2016-01-15
modified:
excerpt: Projects I worked on
image:
  feature:
  teaser:
  thumb:
permalink: /portfolio/
---

<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
