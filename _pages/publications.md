---
layout: page
permalink: /publications/
title: publications
description: 
years: [2023]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
### conference 
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conference-papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

### workshop 
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f workshop-papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
