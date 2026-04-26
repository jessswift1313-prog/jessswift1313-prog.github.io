---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true

---

# Projects

{% for project in site.projects %}

  <h2>
    <a href="{{ project.url }}">{{ project.title }}</a>
  </h2>

  <p>{{ project.excerpt }}</p>

  <hr>

{% endfor %}
