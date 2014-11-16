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
        <img src="{{ project.image }}" alt="">
        <h1>{{ project.title }}</h1>
        <time>{{ project.date | date: "%-d %B %Y" }}</time>
        <p>{{ project.excerpt }}</p>
      </article>
    </a>
  </li>
  {% endfor %}
</ul>
