---
layout: activity
title: "Added affected pages to posts, rebuild [workwithzack.com](https://workwithzack.com) on github pages"
duration: "~15 minutes + 1 hour in the evening"
date: 2022-11-23
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
  <li>https://rebuild.zackgilbert.com/activity/*</li>
  <li><a href="https://workwithzack.com">https://workwithzack.com</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
