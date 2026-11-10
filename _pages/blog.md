---
layout: page
title: blog
permalink: /blog/
description: Research notes on trustworthy and human-centered AI.
nav: true
nav_order: 3
---

{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <h3><a class="post-title" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.description | default: post.excerpt }}</p>
  </li>
  {% endfor %}
</ul>
{% else %}
<p>No posts yet.</p>
{% endif %}
