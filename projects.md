---
layout: default
title: Projects
permalink: /projects/
---

<h1>Woo!</h1>

<ul class="project-list">
  {% for project in site.categories.project %}
  <li>
    <a href="{{ project.url }}">
      <article class="project-tile">
        <h1>{{ project.title }}</h1>
        {{ project.excerpt }}
        <img src="{{ project.image }}" alt="">
      </article>
    </a>
  </li>
  {% endfor %}
</ul>
