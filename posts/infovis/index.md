---
layout: archive
title: "文章"
date: 2018-1-03T23:11:36-04:00
modified:
excerpt: "学习笔记"
tags: []
image: 
  feature: earth.jpg
  teaser:
---

在此留下我在可视化学习途中收集到的信息

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
