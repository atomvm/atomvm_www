---
layout: default
title: News
permalink: /news/
---

<!--
See README.md for instructions on adding a news post
-->

<a href="/index.html">home..</a>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
