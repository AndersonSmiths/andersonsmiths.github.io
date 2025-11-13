---
layout: default
title: Projects
permalink: /projects/
---
{% assign coursework  = site.projects | where: "category", "coursework" %}
{% assign hyperloop   = site.projects | where: "category", "hyperloop" %}
{% assign internship  = site.projects | where: "category", "internship" %}
{% assign machine     = site.projects | where: "category", "machine-shop" %}
{% assign personal    = site.projects | where: "category", "personal" %}

{%- assign coursework_img = '/assets/images/hub-coursework.jpg' | relative_url -%}
{%- assign hyper_img = '/assets/images/hub-hyperloop.jpg' | relative_url -%}
{%- assign intern_img = '/assets/images/hub-internship.jpg' | relative_url -%}
{%- assign machine_img = '/assets/images/hub-machine.jpg' | relative_url -%}
{%- assign personal_img = '/assets/images/hub-personal.jpg' | relative_url -%}
{%- assign all_img = '/assets/images/hub-all.jpg' | relative_url -%}

<div class="hub container my-5">
  <h1 class="projects-title">Projects</h1>
  <!-- Row 1: Coursework • Hyperloop • Internships -->
  <div class="row g-4 justify-content-center">
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/coursework/' | relative_url }}">
        <img class="hub-img" src="{{ coursework_img }}" alt="Coursework">
        <span>Coursework</span>
      </a>
    </div>
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/hyperloop/' | relative_url }}">
        <img class="hub-img" src="{{ hyper_img }}" alt="Hyperloop">
        <span>Hyperloop</span>
      </a>
    </div>
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/internships/' | relative_url }}">
        <img class="hub-img" src="{{ intern_img }}" alt="Internships">
        <span>Internships</span>
      </a>
    </div>
  </div>

  <!-- Row 2: Machine Shop • Personal Projects • All Projects (last) -->
  <div class="row g-4 justify-content-center mt-2">
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/machine-shop/' | relative_url }}">
        <img class="hub-img" src="{{ machine_img }}" alt="Machine Shop">
        <span>Machine Shop</span>
      </a>
    </div>
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/personal/' | relative_url }}">
        <img class="hub-img" src="{{ personal_img }}" alt="Personal Projects">
        <span>Personal Projects</span>
      </a>
    </div>
    <div class="col-10 col-sm-6 col-md-4 col-lg-3">
      <a class="hub-card" href="{{ '/projects/all/' | relative_url }}">
        <img class="hub-img" src="{{ all_img }}" alt="All Projects">
        <span>All Projects</span>
      </a>
    </div>
  </div>
</div>