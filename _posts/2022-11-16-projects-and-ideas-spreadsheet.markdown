---
layout: activity
title: "First pass at putting together a [Projects + Ideas spreadsheet](https://docs.google.com/spreadsheets/d/12vxRYLiDF-cSlhvIf2hHiJ6oE1ZQD79s41yMkZIYIS0/edit?usp=sharing)"
duration: "~2 hours of data entry in the evening"
date: 2022-11-16
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
