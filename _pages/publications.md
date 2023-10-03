---
layout: page
permalink: /publications/
title: publications
description:
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">
  <div class="photo-container">
    <img src="assets/img/TREE_Cover.jpg" alt="Photo 1">
    <img src="assets/img/CopeiaJPEG.jpg" alt="Photo 2">
    <img src="assets/img/PsammodynastescoverJPEG.jpg" alt="Photo 3">
  </div>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
  
</div>
