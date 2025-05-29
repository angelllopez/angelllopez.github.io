---
layout: default
title: Blog
---

# 🚀 Blog
## Recent Posts
{% for post in site.posts %}
  - [{{ post.title | escape }}]({{ post.url | escape }})
{% endfor %}