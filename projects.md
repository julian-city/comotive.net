---
layout: default
title: Projects
permalink: /projects/
---

# Projects

{% if site.projects.size > 0 %}
<ul class="card-list">
  {% for project in site.projects %}
  <li class="card">
    <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
  </li>
  {% endfor %}
</ul>
{% else %}
Coming soon.
{% endif %}
