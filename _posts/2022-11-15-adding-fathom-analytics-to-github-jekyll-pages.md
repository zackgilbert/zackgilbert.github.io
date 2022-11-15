---
layout: post
title: Adding Fathom Analytics to Github Jekyll Pages
date: 2022-11-15 17:50:00 -0000
categories: REBUILD ANALYTICS FATHOM GITHUB PAGES JEYKYLL
---

# Adding Fathom Analytics to Github Jekyll Pages

While deciding to work on this [Rebuild](https://rebuild.zackgilbert.com) project, I wanted to do a better job of utilizing technologies and services that can make my work more efficient. I decided to use the [Github Pages](https://docs.github.com/en/pages), which are built off Jekyll and use Markdown instead of writing native HTML. They allow me to edit files directly in Github but still taking advantage of the core version control. To keep things as simple as possible, I went with the Github supported [minimal](https://github.com/pages-themes/minimal) theme. Unfortunately, while it does have built in Google Analytics support, it did not natively support my preferred analytics software (and sponsor of this project): [Fathom Analytics](https://usefathom.com/ref/DNQLHG).

Luckily, adding custom support was super easy. The theme has a [dedicated header file](https://github.com/pages-themes/minimal/blob/master/_includes/head-custom.html) (`_includes/head-custom.html`) in the layout that lets you insert regular html (like a script tag). I just inserted my Fathom script tag into this file ([I had to add it myself to override the default theme's template](https://github.com/zackgilbert/zackgilbert.github.io/blob/main/_includes/head-custom.html)). I just replaced the Google Analytics include because I wasn't going to be using it at all. 

My file ended up being: 
```html
<!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Fathom - beautiful, simple website analytics -->
<script src="https://cdn.usefathom.com/script.js" data-site="STHKFIFG" defer></script>
<!-- / Fathom -->

<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="{{ '/favicon.ico' | relative_url }}" -->

<!-- end custom head snippets -->
```

That's it.
