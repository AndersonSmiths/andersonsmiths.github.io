---
layout: default
title: Hyperloop Projects
permalink: /projects/hyperloop/
image: /assets/images/hub-hyperloop.jpg
---
<div class="gallery-container">
  <div class="project-gallery">
    {% assign filtered = site.projects | where: "category", "hyperloop" %}
    {% for project in filtered %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>