---
layout: single
title: "News"
permalink: /news/
---

<div class="news-list">
  {% for post in site.posts %}
    {% if post.categories contains 'news' %}
      <article class="news-post">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <time datetime="{{ post.date | date: '%Y-%m-%d' }}">
          {{ post.date | date: '%Y年%m月%d日' }}
        </time>
        <p>{{ post.excerpt }}</p>
      </article>
    {% endif %}
  {% endfor %}
</div>
