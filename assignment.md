---
layout: page

nav_exclude: true
description: The weekly event schedule.
---

# 课时安排

### 2023年秋季，第2周至第10周

{% for assignment in site.assignments %}
{{ assignment }}
{% endfor %}
