---
layout: home
title: "My Builds"
---

<div class="welcome">
  <h1>Welcome to My Builds</h1>
  <p>Here I document my carpentry, DIY, and physical projects.  
     Each project has its own page with photos, notes, and details.</p>
</div>

<hr>

<h2>Recent Builds</h2>

{% for post in site.posts %}
<div class="post-preview">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}
