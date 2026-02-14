---
layout: default
title: Blog
permalink: /blog/
---

<header class="top">
  <h1>blog</h1>
  <a href="{{ '/' | relative_url }}">home →</a>
</header>

<section>
  <h2>posts</h2>
  {% if site.posts.size > 0 %}
    <ul class="blog-list">
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
          <span class="muted">— {{ post.date | date: "%b %-d, %Y" }}</span>
        </li>
      {% endfor %}
    </ul>
  {% else %}
    <p class="muted">No posts yet.</p>
  {% endif %}
</section>
