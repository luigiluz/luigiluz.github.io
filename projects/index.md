---
title: Projects
---

{% for project in site.projects %}
  <h2> {{ project.title }} </h2>
  <p>{{ project.description }}</p>
{% endfor %}