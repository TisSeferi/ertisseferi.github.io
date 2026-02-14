---
layout: default
---

# Ertis Seferi

### MS Computer Science — Robotics, Computer Vision & Machine Learning

I am a graduate student at Binghamton University focused on robotics,
reinforcement learning, and computer vision systems. My research interests
include embodied AI, robot perception, and learning-based control.

---

## Featured Projects

<div class="card-grid">
{% for project in site.projects %}
<div class="card">
  <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
  <p>{{ project.description }}</p>
</div>
{% endfor %}
</div>
