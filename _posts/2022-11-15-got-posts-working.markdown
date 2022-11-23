---
layout: activity
title: "Got posts working with [Adding Fathom Analytics to Github Jekyll Pages](https://rebuild.zackgilbert.com/2022/11/15/adding-fathom-analytics-to-github-jekyll-pages)"
duration: "~2 hours of writing in the morning, during lunch and in the evening"
date: 2022-11-15
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
