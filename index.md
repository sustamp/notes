---
layout: home
title: notes
---
## 文章列表
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a><span>    ({{ post.date | date_to_string }})    </span>
    </li>
  {% endfor %}
</ul>
