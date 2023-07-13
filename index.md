---
title: Welcome to my blog
---

# Hello!

Welcome to my blog.

## What is this, though?

Just a demo! Enjoy! :)

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
