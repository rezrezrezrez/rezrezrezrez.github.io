---
layout: page
permalink: /talks/
title: talks
description:
years: [2026, 2025, 2024]
nav: true
nav_order: 4
---
<!-- _pages/publications.md -->
Selected talks.

<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>