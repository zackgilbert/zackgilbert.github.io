---
layout: activity
title: "Installed analytics via the wonderful [Fathom Analytics](https://usefathom.com/ref/DNQLHG) (sponsor)"
duration: "~15 minutes"
date: 2022-11-14
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
