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

<<<<<<< HEAD
=======
## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/dbtek/jekyll-bootstrap-3)!


>>>>>>> dae66a174e696f81757bb77ba9193677d0afb832
