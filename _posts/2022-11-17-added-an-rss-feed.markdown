---
layout: activity
title: "Added an [RSS feed](https://rebuild.zackgilbert.com/feed.xml) for posts"
duration: "~10 minutes in the morning"
date: 2022-11-17
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
  <li><a href="https://rebuild.zackgiblert.com/feed.xml">https://rebuild.zackgiblert.com/feed.xml</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
