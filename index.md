---
layout: default
title: Home
---

<h2 style="border-bottom: none;">Posts</h2>
<ul>
  {% for post in site.posts %}
    <li style="margin-bottom: 0.5em;">
      <a href="{{ post.url }}">{{ post.title }}</a> <small>{{ post.date | date: "%b %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>