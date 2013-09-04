---
layout: tech
title: 文章存档
section: Past

feed: /feed
keywords: rails on ruby,ruby,mac,R,psychology,brain
---

文章存档
========

This is the complete archive of posts from _[欧阳的技术笔记](/tech)_
in reverse chronological order.

{% for post in site.categories.tech %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  </p>
  <p class="excerpt">{{ post.excerpt }}</p>
</div>
{% endfor %}
