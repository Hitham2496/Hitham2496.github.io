---
layout: page
permalink: /publications/
title: Publications
description: Publications produced throughout my academic career
years: [2023,2022]
nav: true
nav_order: 1
---

Shown below are my upcoming research publications for work undertaken
during my time as a Ph.D. candidate researcher at the IPPP, Durham University.

The work is currently ongoing and thus the publication dates are
approximate - reflecting our expectation of when they will be published.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
