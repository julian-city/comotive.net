---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% if site.posts.size > 0 %}
<ul class="card-list">
  {% for post in site.posts %}
  <li class="card">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p class="card-meta">{{ post.date | date: "%B %Y" }}</p>
  </li>
  {% endfor %}
</ul>
{% else %}
Coming soon.
{% endif %}
