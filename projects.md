---
layout: page
title: Projects
permalink: /projects/
---

<div class="card-grid">
{% for project in site.projects %}
<div class="card">
  <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
  <p>{{ project.description }}</p>
</div>
{% endfor %}
</div>
