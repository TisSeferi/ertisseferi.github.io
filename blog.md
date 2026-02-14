---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
<div class="card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
  <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
</div>
{% endfor %}

{% if site.posts.size == 0 %}
*No posts yet. Check back soon!*
{% endif %}
