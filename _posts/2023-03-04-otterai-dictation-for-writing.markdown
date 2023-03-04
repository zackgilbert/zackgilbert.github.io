---
layout: activity
title: "Using [Otter.ai](https://otter.ai/referrals/O4RM4SZB) dictation for article and newsletter writing"
duration: "~1 hour of dictation in the car, 2 hours of writing and editing"
date: 2023-03-04
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild, referral, newsletter
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
