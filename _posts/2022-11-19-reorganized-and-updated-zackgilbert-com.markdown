---
layout: activity
title: "Reorganized and updated [zackgilbert.com](https://zackgilbert.com) & [zackgilbert.com/concerts](https://zackgilbert.com/concerts). Added a [https://zackgilbert.com/now](/now) page."
duration: "~3 hours while baby slept"
date: 2022-11-19
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

<h3>Affected Pages</h3>
<ul>
  <li><a href="https://zackgilbert.com">https://zackgilbert.com</a></li>
  <li><a href="https://zackgilbert.com/concerts">https://zackgilbert.com/concerts</a></li>
  <li><a href="https://zackgilbert.com/now">https://zackgilbert.com/now</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
