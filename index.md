---
layout: page
title: Smart Home Blog
tagline: 
---
{% include JB/setup %}

## Liste der letzen Veröffentlichungen

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

