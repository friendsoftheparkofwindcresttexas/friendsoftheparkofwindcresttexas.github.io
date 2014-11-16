---
layout: default
title: Projects
permalink: /projects/
---

# Projects

<ul class="project-list">
  {% for project in site.categories.project %}
  <li>
    <a href="{{ project.url }}">
      <article class="project-tile">
        <img src="{{ project.image }}" alt="">
        <h1>{{ project.title }}</h1>
        <time>{{ project.date | date: "%B %-d, %Y" }}</time>
        <p>{{ project.excerpt }}</p>
      </article>
    </a>
  </li>
  {% endfor %}
</ul>
