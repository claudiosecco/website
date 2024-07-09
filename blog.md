---
layout: default
title: Blog
language: pt-BR
---

<h1>Últimos Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
