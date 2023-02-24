---
layout: activity
title: "Week 4 of Sean Johnson's Building an Intentional Life mentoring"
duration: "~2 hours of homework in evenings and weekend, 1.5 hours for group meeting during work day"
date: 2023-02-15
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild, intentionally
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
