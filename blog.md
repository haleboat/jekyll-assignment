---
layout: default
title: Blog
---
<h2>Latest Posts</h2>
<ul>
  {% for post in site.posts %}
  <li>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>
      Date: {{ post.date | date_to_string }}
    </p>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>