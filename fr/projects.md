---
layout: default
title: Projets
permalink: /projects/
lang: fr
---

# {{ site.data.i18n[site.active_lang].nav.projects }}

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
{{ site.data.i18n[site.active_lang].coming_soon }}
{% endif %}
