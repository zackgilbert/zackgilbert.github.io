---
layout: activity
title: "Fleshed out some Rules and Guidelines for Rebuild."
duration: "~15 minutes during lunch break"
date: 2022-12-01
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
  <li>https://rebuild.zackgilbert.com</li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
