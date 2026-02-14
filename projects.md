---
layout: page
title: Projects
permalink: /projects/
---

<div class="card-grid">
{% for project in site.projects %}
<div class="card">
  <h3><a href="{{ project.repo }}" target="_blank">{{ project.title }}</a></h3>
  <p>{{ project.description }}</p>
</div>
{% endfor %}
</div>
