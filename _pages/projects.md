---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true

---

{% for project in site.projects %}
  <article class="archive__item">
    <h2 class="archive__item-title">
      <a href="{{ project.url }}">{{ project.title }}</a>
    </h2>
    <p class="archive__item-excerpt">
      {{ project.excerpt }}
    </p>
  </article>
{% endfor %}
