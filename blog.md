---
layout:  post
title:   "Bloque"
permalink:  /blogue/
---
### Voici la page du blog
<hr>
    <section class="container"></section>
        <ul>
            {% for post in site.posts %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
            {% endfor %}
        </ul>
    </section>
