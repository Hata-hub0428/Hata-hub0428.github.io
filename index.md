---
layout: default
title: Home
---

# Haru's Blog

## 投稿記事一覧
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y/%m/%d" }} - <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
