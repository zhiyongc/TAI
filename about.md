---
layout: page
title: 1. 课程简介
nav_exclude: true
description: >-
    Course policies and information.
---

# 人工智能
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# 课程简介

## 课程内容

主讲教师：崔志勇
助教： 李诚博，赵艺萱
教室： J5-302

### 参考资料



## 校历课时安排

{% for module in site.modules %}
{{ module }}
{% endfor %}

<!-- 
# 授课团队

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
{% endfor %} -->
{% endif %}

<!-- # 上课及答疑时间

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %} -->