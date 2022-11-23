---
layout: activity
title: "Added a [/web](https://zackgilbert.com/web) and navigation to [zackgilbert.com](https://zackgilbert.com) pages."
duration: "~2 hours while baby slept"
date: 2022-11-21
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
