---
layout: activity
title: "Sent out second post in my [Emotional Investors' Update](https://zackgilbert.substack.com/p/emotional-investors-update-2-2023)"
duration: "~2 hours of editing a 20 minute audio dictation while on a daddy weekend"
date: 2023-03-05
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild, newsletter
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
