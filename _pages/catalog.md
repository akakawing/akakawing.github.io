---
layout: with-title
title: 其他目录
permalink: /catalog/
---

### 计算机

<ul>
    {% for post in site.posts %}
      {% if post.tags contains 'it' %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

### 其他

<ul>
    {% for post in site.posts %}
      {% if post.tags contains 'else' %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>



