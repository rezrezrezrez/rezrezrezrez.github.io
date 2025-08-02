---
layout: page
permalink: /talks/
title: talks
description:
years: [2025]
nav: true
nav_order: 4
---
<!-- _pages/talks.md -->

<div class="talks">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>