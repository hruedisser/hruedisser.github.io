---
layout: page
permalink: /publications/
title: publications
description: publications by year.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

{% bibliography %}

</div>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
