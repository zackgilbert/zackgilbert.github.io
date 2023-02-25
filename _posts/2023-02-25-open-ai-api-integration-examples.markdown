---
layout: activity
title: "Working on familiarizing myself with [OpenAI API integration examples](https://dev.to/kanehooper/creating-an-intelligent-knowledge-base-qa-app-with-gpt-3-and-ruby-15ke)."
duration: "~2 hours Saturday morning while the kid was with the grandparents"
date: 2023-02-25
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
