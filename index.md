---
layout: home
title: "Polymat Builds"
---

# Welcome to Polymat Builds

Explore my carpentry, DIY, and other physical projects.  
Each project has its own post with photos, notes, and progress updates.

---

## Recent Projects

{% for post in site.posts %}
<div class="post-preview">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}
