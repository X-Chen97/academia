---
layout: page
permalink: /presentations/
title:  Presentations
description: Some of my posters and oral presentations.
years: [2022]
nav: true
---
<!-- _pages/presentations.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f slides -q @*[year={{y}}]* %}
{% endfor %}

</div>
