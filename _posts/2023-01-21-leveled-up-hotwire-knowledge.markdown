---
layout: activity
title: "Leveled up Hotwire knowledge via [Andrea Fomera's Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire) course"
duration: "~5 hours total over 3 Satursdays during naps and momma/baby adventures"
date: 2023-01-21
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild, forum, courses
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

<h3>Helpful Resources</h3>
<ul>
  <li><a href="https://store.afomera.dev/learn-hotwire">Learn Hotwire by Building a Forum</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
