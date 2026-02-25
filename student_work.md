---
title: Student Work
layout: base
date: 2025-09-30
homepage: TRUE
position: 2
summary: This is where students work from Jessica Rowlands's SUS 364 class will be located.
thumbnail: assets/images/Cleve-van_construction-tower-babel.jpg
---

## Student Work

Summary of the student's contributions to the website.

{% assign all_pages = site.pages %} {% assign cards = all_pages | where_exp: "p", "p.path contains 'sust-student-work/'" %}

{% include nav/card-grid.html cards=cards %}
