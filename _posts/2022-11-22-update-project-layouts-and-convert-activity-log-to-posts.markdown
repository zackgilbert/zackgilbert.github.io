---
layout: activity
title: "Update project layouts and convert activity log to posts"
duration: "~2 hours in the evening"
date: 2022-11-22
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
  <li><a href="https://rebuild.zackgilbert.com">https://rebuild.zackgilbert.com</a></li>
  <li><a href="https://rebuild.zackgilbert.com/feed.xml">https://rebuild.zackgilbert.com/feed.xml</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
