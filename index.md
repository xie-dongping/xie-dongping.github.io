---
layout: page
title: 谢东平的网志
tagline: 电车仿真 Modelica
---
{% include JB/setup %}

    
## 文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

