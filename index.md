---
layout: default
---

<div class="hero">
  <h1 class="hero-name">Ertis Seferi</h1>
  <p class="hero-tagline">MS Computer Science — Robotics, Computer Vision & Machine Learning</p>
</div>

I am a graduate student at Binghamton University focused on robotics,
reinforcement learning, and computer vision systems. My research interests
include embodied AI, robot perception, and learning-based control.

---

## Featured Projects

<div class="card-grid">
{% for project in site.projects %}
<div class="card">
  <h3><a href="{{ project.repo }}" target="_blank">{{ project.title }}</a></h3>
  <p>{{ project.description }}</p>
</div>
{% endfor %}
</div>
