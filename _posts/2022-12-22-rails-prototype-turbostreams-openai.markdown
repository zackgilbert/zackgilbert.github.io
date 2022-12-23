---
layout: activity
title: "Got a Rails protoype working w/ turbostreams for a simple OpenAI proof of concept project."
duration: "~2 hours in evening while baby was away with grandparents"
date: 2022-12-22
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
