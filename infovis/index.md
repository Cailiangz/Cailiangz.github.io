---
layout: archive
title: "信息可视化作品集"
date: 2018-1-7 19:07:50 +0800
modified:
excerpt: ""
tags: []
image: 
  teaser: 期末作品仪表板.png
---
<a href="https://public.tableau.com/views/3_1031/1_1?:embed=y&:display_count=yes" target="_blank"><img src="https://cailiangz.github.io/images/期末作品仪表板.png" alt="teaser" itemprop="image">
<br/>信息可视化作品
<div class="tiles">
{% for post in site.categories.infovis%}
  {% include post-grid.html %}
{% endfor %}
</div>
