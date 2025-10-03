---
layout: default
title: "Home"
---

# Welcome to Polymat Builds

Here you can explore my carpentry, DIY, and other physical projects.  
Each project has its own post with photos, notes, and progress updates.

## Recent Projects

{% for post in site.posts %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
