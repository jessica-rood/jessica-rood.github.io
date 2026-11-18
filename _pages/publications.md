---
layout: page
permalink: /research/
title: Research
description: Working papers, reports and data, and works in progress.
nav: true
nav_order: 1
---

<!-- _pages/publications.md (rendered at /research/) -->

<div class="publications">

  <h2 class="bibliography-section-heading">Working Papers</h2>
  {% bibliography -q @*[category=working_paper] %}

  <h2 class="bibliography-section-heading">Reports and Data</h2>
  {% bibliography -q @*[category=report] %}

  <h2 class="bibliography-section-heading">Works in Progress</h2>
  {% bibliography -q @*[category=work_in_progress] %}

</div>
