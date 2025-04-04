---
title: Le Backlog du Daron
---

# Le Backlog du Daron

Bienvenue sur le Backlog du Daron !

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>