---
layout: home
title: STAT 5700 Probability
nav_exclude: false
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

This is the course website for Dr. Fitzgerald's section of STAT 5700, taught at Villanova University in Fall 2025.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% endif %}