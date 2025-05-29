---
layout: default
title: Blog
---

# 🚀 Blog
## Recent Posts
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}