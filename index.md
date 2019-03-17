---
title: The Sacred Chalice of Rixx
permalink: /
---
This is the GitHub page for the [Sacred Chalice of Rixx](./about).

## Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>