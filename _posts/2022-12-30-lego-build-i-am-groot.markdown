---
layout: activity
title: "Lego Build - [I am Groot](https://www.lego.com/en-us/product/i-am-groot-76217)"
duration: "~2 hours total over 3 nights each in the evening"
date: 2022-12-30
permalink: /:categories/:year-:month-:day
author: Zack Gilbert
categories: activity
tags: rebuild, lego
---

<small>{{ page.date | date: "%A, %B %-d, %Y" }}</small>
<h1>{{ page.title }}</h1>

<p class="view">by {{ page.author | default: site.author }}</p>

<p>{{ page.duration }}</p>

<h3>Photos</h3>
<ul>
  <li><img src="https://pbs.twimg.com/media/FlCg_iJWYAA0VEQ?format=jpg&name=large"></li>
  <li><img src="https://pbs.twimg.com/media/FlRfVc9WQAAc2nu?format=jpg&name=large"></li>
</ul>

<h3>Helpful Resources</h3>
<ul>
  <li><a href="https://www.lego.com/en-us/product/i-am-groot-76217">I am Groot 76217 | Marvel | Buy online at the Official LEGO® Shop US</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
