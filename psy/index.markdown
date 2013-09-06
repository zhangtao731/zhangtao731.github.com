---
layout: psy
title: Home
section: Home

feed: /feed
keywords: 心理学,社会心理学,心理学博客,心理学家
---

改变世界，从改变自己开始
==========================================

<p><a href='/feed'><img title='Atom feed of recent posts' class='right' src='/files/css/feed-icon-14x14.png' alt='Feed icon' /></a> A <a href='/feed'>feed</a> of the most recent posts is also available.</p>

最近的文章
------------

{% for post in site.categories.psy limit:5 %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  </p>
  <p class="excerpt">{{ post.excerpt }}</p>
</div>
{% endfor %}

<p>
<a href="past.html">更早的文章 &rarr;</a>
</p>