---
layout: archive
title: "Tableau作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "展示学生的信息可视化作品"
tags: []
image: 
  feature: 
  teaser:
--- 

<iframe src="https://public.tableau.com/views/_18328/1_2?:embed=y&:display_count=yes&publish=yes" width="500px" height="420px" frameborder="0"></iframe>

<div class="tiles">
{% for post in site.categories.tab %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 tab 的列出来-->