---
title: "Home"
---
# Welcome to My Blog!
**Recent Posts:**
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}