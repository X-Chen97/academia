---
layout: page
permalink: /presentations/
title: Presentations
years: [2022]
nav: true
---
<!-- _pages/presentations.md -->
<div class="presentations">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
