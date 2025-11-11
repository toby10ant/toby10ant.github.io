---
layout: default
title: Home
---

# Welcome

This is a basic Jekyll site running on GitHub Pages.  
Add posts in the `_posts/` folder to get started.

Latest posts:
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> – {{ post.date | date_to_string }}</li>
  {% endfor %}
</ul>