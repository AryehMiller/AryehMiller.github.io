---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021, 2020, 2019, 2018, 2017]
nav: true
---

For complete list of publications, please refer to my <a href="https://scholar.google.com/citations?user=JOhxhg4AAAAJ&hl=en">Google Scholar profile</a>.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
