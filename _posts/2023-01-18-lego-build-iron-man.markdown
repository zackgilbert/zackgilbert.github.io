---
layout: activity
title: "Lego Build - [Iron Man Figure](https://www.lego.com/en-us/product/iron-man-figure-76206)"
duration: "~3 hours total over 4 nights in the evening"
date: 2023-01-18
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
  <li><img src="https://pbs.twimg.com/media/FmiJhGsXoAIC1Ec?format=jpg&name=medium"></li>
  <li><img src="https://pbs.twimg.com/media/FmpArXdXEAIDtJt?format=jpg&name=medium"></li>
  <li><img src="https://pbs.twimg.com/media/FmuPrygXoAAGD5M?format=jpg&name=medium"></li>
  <li><img src="https://pbs.twimg.com/media/FmzUxHfWQAEXqHc?format=jpg&name=medium"></li>
</ul>

<h3>Helpful Resources</h3>
<ul>
  <li><a href="https://www.lego.com/en-us/product/iron-man-figure-76206">Iron Man Figure 76206 | Marvel | Buy online at the Official LEGO® Shop US</a></li>
</ul>

{% if page.tags %}
  <small>tags: <em>{{ page.tags | join: "</em> - <em>" }}</em></small>
{% endif %}
