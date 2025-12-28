---
layout: default
title: "first"
date: 2025-01-01
---

e
## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }})  
  <small>{{ post.date | date: "%Y-%m-%d" }}</small>
{% endfor %}