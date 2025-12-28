---
layout: default
title: Home
---

Hello,
This is a personal site where I write about my programming projects, physics, math curiosities, videogames, and whatever I'm interested in.

## Recent posts
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}