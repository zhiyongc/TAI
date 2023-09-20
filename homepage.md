---
layout: home
title: 课程简介
# nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Just the Class
---

# 人工智能
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

<!-- # 课程简介 -->

## 课程内容

* 本课程作为介绍人工智能概况与基础知识的课程，主要介绍人工智能相关知识，以机器学习、深度学习及其在交通领域中的应用 
* 主要面向具有一定数理基础及编程能力的本科生（大三及大四学生），学生最好能够熟练运用Python，熟悉Numpy、Pandas、matplolib等基础工具包，了解scikit-learn、PyTorch等机器学习、深度学习编程工具 :frog:
* 本课程以结合知识讲授与代码实践为目标，为学生提供多个代码练习，并以自由选题的课程设计作为考核方式，着重强调提升学生理论与实践相结合的动手能力 
 
参考资料

* :closed_book:《[Machine Learning for Transportation Research and Applications](https://books.google.com.hk/books?hl=en&lr=&id=1aCSEAAAQBAJ&oi=fnd&pg=PP1&dq=info:mxQeWRErljgJ:scholar.google.com&ots=Nw1sFgknt-&sig=1le41OEaPMD6L7PUaEIcsOH3DsM&redir_esc=y#v=onepage&q&f=false)》, Yinhai Wang, Zhiyong Cui, Ruimin  Ke, Elsevier, 2023
* :closed_book:《神经网络与深度学习》，邱锡鹏，复旦大学, 2020  [[下载]({{ site.baseurl }}/Files/神经网络与深度学习-复旦大学-邱锡鹏.pdf)]

## 课程设计（大作业）

* 课程设计以小组为单位，每队3-4人，**第三次课**前完成组队 :v:
* 每个小组通过调研、阅读文献、与老师或助教沟通，确定题目，**第六次课**前确定题目
  * 选题以 “人工智能 + 专业” 为大方向，以小组兴趣为主
* 课程设计项目答辩在进行**第十一周** :boom:



## 课时安排

{% for module in site.modules %}
{{ module }}
{% endfor %}




## 课程时间

2023年秋季，第2周至第10周

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}


## 授课团队
授课教师

{% assign instructors = site.staffers | where: 'role', '授课教师' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', '助教' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
助教

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}







<!-- Just the Class is a GitHub Pages template developed for the purpose of quickly deploying course websites. In addition to serving plain web pages and files, it provides a boilerplate for:

- [announcements](announcements.md),
- a [course calendar](calendar.md),
- a [staff](staff.md) page,
- and a weekly [schedule](schedule.md).

Just the Class is a template that extends the popular [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme, which provides a robust and thoroughly-tested foundation for your website. Just the Docs include features such as:

- automatic [navigation structure](https://just-the-docs.github.io/just-the-docs/docs/navigation-structure/),
- instant, full-text [search](https://just-the-docs.github.io/just-the-docs/docs/search/) and page indexing,
- and a set of [UI components](https://just-the-docs.github.io/just-the-docs/docs/ui-components) and authoring [utilities](https://just-the-docs.github.io/just-the-docs/docs/utilities).

## Getting Started

Getting started with Just the Class is simple.

1. Create a [new repository based on Just the Class](https://github.com/kevinlin1/just-the-class/generate).
1. Update `_config.yml` and `README.md` with your course information. [Be sure to update the url and baseurl](https://mademistakes.com/mastering-jekyll/site-url-baseurl/).
1. Configure a [publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages). Your course website is now live!
1. Edit and create `.md` [Markdown files](https://guides.github.com/features/mastering-markdown/) to add more content pages.

Just the Class has been used by instructors at Stanford University ([CS 161](https://stanford-cs161.github.io/winter2021/)), UC Berkeley ([Data 100](https://ds100.org/fa21/)), UC Santa Barbara ([CSW8](https://ucsb-csw8.github.io/s22/)), Northeastern University ([CS4530/5500](https://neu-se.github.io/CS4530-CS5500-Spring-2021/)), and Carnegie Mellon University ([17-450/17-950](https://cmu-crafting-software.github.io/)). Share your course website and find more examples in the [show and tell discussion](https://github.com/kevinlin1/just-the-class/discussions/categories/show-and-tell)!

### Local development environment

Just the Class requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler. To setup a local development environment, clone your template repository and follow the GitHub Docs on [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll). -->
