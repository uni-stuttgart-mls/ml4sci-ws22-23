---
layout: page
title: Who We Are
nav_order: 3
description: A listing of the seminar staff.
---

## Seminar Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

