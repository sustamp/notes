---
layout: default
title: notes
---

## 文章列表
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><span>(({{ post.date | date_to_string }})</span>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
