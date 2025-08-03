---
layout: page
permalink: /talks/
title: talks
description: Selected talks. For a full list, see my <a href="/assets/pdf/Rezwan_Hoque_CV.pdf">CV</a>.
years: [2025, 2024]
nav: true
nav_order: 4
---
<!-- _pages/publications.md -->

<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>