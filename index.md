---
layout: home
title: "My Builds"
---

# Welcome to Polymat Builds

Here you can explore my carpentry, DIY, and other physical projects.  
Each project has its own post with photos, notes, and progress updates.

---

## Recent Projects

{% for post in site.posts %}
<div class="post-preview">
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}
