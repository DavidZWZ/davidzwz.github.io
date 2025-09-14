---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
# years: [2024, 2023, 2021]
nav: true
nav_order: 2
---

<div class="alert alert-info">
This publication list is no longer maintained. For the most recent papers and full publication list, please visit my <a href="https://scholar.google.com/citations?user=TazcjBIAAAAJ&hl=en">Google Scholar profile</a>.
</div>

<!-- _pages/publications.md -->
<div class="publications">
  {% bibliography %}
  <!-- {% for y in page.years %}
    <h2 class="year">{{y}}</h2>
    {% bibliography -f papers -q @*[year={{y}}]* %}
  {% endfor %} -->
</div>
