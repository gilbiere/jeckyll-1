---
layout: post
title: "Bloque"
permalink: /blogue/
---

### Voici la page du blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
