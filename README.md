---
layout: home
title: Important Course Info
nav_exclude: false
nav_order: 1
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