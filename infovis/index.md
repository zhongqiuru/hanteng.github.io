---
layout: archive
title: "Tableau作品集"
date: 2017-12-30T11:40:45-04:00 
---
< a href="< a href="https://public.tableau.com/views/_18328/1_1?:embed=y&:display_count=yes&publish=yesDashboard1?:showVizHome=no&:embed=true" target="_blank">< img src="/images/123.png" width="650" height="500" border="0" /></ a> 
<div class="tiles">
{% for post in site.categories.tab %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->