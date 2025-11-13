---
layout: default
title: Coursework Projects
permalink: /projects/coursework/
image: /assets/images/hub-coursework.jpg
---
<div class="gallery-container">
  <div class="project-gallery">
    {% assign filtered = site.projects | where: "category", "coursework" %}
    {% for project in filtered %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}">
          <p>{{ project.title }}</p>
        </a>
      </div>
    {% endfor %}
  </div>
</div>