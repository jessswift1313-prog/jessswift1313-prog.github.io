---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true

---

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url | relative_url }})

{{ project.excerpt }}

---
{% endfor %}
