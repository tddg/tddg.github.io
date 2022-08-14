---
layout: page
permalink: /teaching/
title: teaching
nav: true
display_categories: [uva, gmu]
nav_order: 3
---

<!-- pages/projects.md -->
<div class="projects">
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_courses = site.courses | where: "category", category | reverse -%}
    {% for course in categorized_courses %}
      {% include course.html %}
    {% endfor %}
  {% endfor %}
</div>
