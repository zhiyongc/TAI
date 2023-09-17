---
layout: page
title: 3. 授课团队
# nav_exclude: true
description: A listing of all the course staff members.
---

<!-- # Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`. -->

## 授课教师

{% assign instructors = site.staffers | where: 'role', '授课教师' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', '助教' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## 助教

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
