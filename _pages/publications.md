---
layout: page
permalink: /research/
title: research
description: Working papers and works in progress, organized by stage.
nav: true
nav_order: 1
---

<!-- _pages/publications.md (rendered at /research/) -->

<div class="publications">

  <h2 class="bibliography-section-heading">Working Papers</h2>
  {% bibliography -q @*[category=working_paper] %}

  <h2 class="bibliography-section-heading">Works in Progress</h2>
  {% bibliography -q @*[category=work_in_progress] %}

  <h2 class="bibliography-section-heading">Active Projects</h2>
  {% bibliography -q @*[category=active_project] %}

</div>
