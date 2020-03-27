---
layout: default
title: Services
---

<ul>
  {% for service in site.services %}
  <li>
    <h2><a href="{{ service.url }}">{{ service.name }}</a></h2>
  </li>
  {% endfor %}
</ul>