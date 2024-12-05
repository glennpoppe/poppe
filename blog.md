---
title: posts
layout: page
description: Posts on topics that interest me
---

Writings on topics that interest me. 

{% for post in site.posts %}
<p>
  <a href="{{ post.url }}">{{ post.title }}</a>
  <br>
  <small>{{ post.date | date_to_string }}</small>
</p>
{% endfor %}
