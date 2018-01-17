---
layout: archive
title: "文章"
date: 2018-1-03T23:11:36-04:00
modified:
excerpt: "学习笔记"
tags: []
image: 
  feature: 偶像大师-真哥（可视化笔记）.jpg
  teaser:
---

记录我在学习可视化时的收获和发现

<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
