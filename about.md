---
layout: default
title: About
permalink: /about/
---

# About Us

Windcrest's Friends of the Park was established in summer 2011 by Mr. Ted Hanes and Mr. Gary Fisher, two concerned residents of the city looking to do whatever they could to help improve Windcrest. Recruiting several other members, they set out on a mission to take care of what they considered the most valuable resource of the city - its parks.

## Leadership

<ul class="tile-list">
  {% for leader in site.data.leaders %}
  <li>
    <article class="tile">
      <img src="{{ leader.image }}" alt="{{ leader.name }} Portrait" class="portrait">
      <h1>{{ leader.name }}</h1>
      <h4>{{ leader.role }}</h4>
      <p>{{ leader.description }}</p>
    </article>
  </li>
  {% endfor %}
</ul>
<br>
