---
layout: default
title: Team Member's
---

<ul>
  {% for lawyer in site.lawyers %}
  <li>
    <h2><a href="{{ lawyer.url }}">{{ lawyer.name }}</a></h2>
    <h3>{{ lawyer.job_title }}</h3>
  </li>
  {% endfor %}
</ul>