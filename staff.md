---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 7
---

# Staff

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## TAs

{% assign staff = site.staffers | where: 'type', 'TA' %}
{% for staffer in staff %}
{{ staffer }}
{% endfor %}

## Tutors

{% assign staff = site.staffers | where: 'type', 'Tutor' %}
{% for staffer in staff %}
{{ staffer }}
{% endfor %}
