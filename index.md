---
layout: home
title: Accueil
permalink: /
---

Ceci est la page index.md.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
