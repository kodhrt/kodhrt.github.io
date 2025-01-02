---
layout: single
title: Posts
permalink: /posts
---

最新記事一覧

{% for post in site.posts %}
<li class="news-item" data-category="{{ post.categories }}">
    <span class="news-date">{{ post.date | date: "%b %-d, %Y" }}</span>
    <a href="{{ post.url | relative_url }}" class="news-title">{{ post.title }}</a>
</li>
{% endfor %}