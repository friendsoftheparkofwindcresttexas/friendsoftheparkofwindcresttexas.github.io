---
layout: default
title: News
permalink: /news/
---

# News

<ul class="news-list">
  {% for article in site.categories.news %}
  <li>
    <a href="{{ article.url }}">
      <article class="news-tile">
        <img src="{{ article.image }}" class="article-snippet-image">
        <h1>{{ article.title }}</h1>
        <p>{{ article.excerpt }}</p> 
      </article>
    </a>
  </li>
  {% endfor %}
</ul>
