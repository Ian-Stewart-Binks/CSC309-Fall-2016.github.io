---
layout: default
title: Announcements
permalink: /announcements/
---

<ul class="posts">
  {% for post in site.posts %}
  <li>
    <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
    {{post.content}}
  </li>
  {% endfor %}
</ul>
