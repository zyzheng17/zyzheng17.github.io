---
layout: page
title: "Photography"
permalink: /photography/
description: "Astrophotography and night sky captures, organised by time and place."
nav: true
nav_order: 3
dark_theme: true
photo_count: 148
shoot_count: 42
years: ["2026", "2025", "2024", "2023", "2022", "2021"]
---

<p class="page-description">{{ page.description }}</p>

<p class="photo-stats">{{ page.photo_count }} photos &middot; {{ page.shoot_count }} shoots &middot; {{ page.years | last }}&ndash;{{ page.years | first }}</p>

<nav class="photo-years">
  {% for y in page.years -%}
  <a href="#y{{ y }}">{{ y }}</a>
  {%- endfor %}
  <button type="button" class="theme-toggle" id="themeToggle">浅色</button>
</nav>

{% for y in site.data.photos %}
<h2 class="photo-year" id="y{{ y.year }}">{{ y.year }}</h2>
{% for g in y.shoots %}
<h3 class="photo-shoot">{{ g.date }} &middot; {{ g.place }}</h3>
<div class="photo-masonry">
  {% for p in g.photos %}
  <figure{% if p.feature %} class="featured"{% endif %}>
    <a href="{{ '/assets/img/photography/' | append: p.file | relative_url }}" class="lightbox-trigger"
       data-caption="{{ g.date }} &middot; {{ g.place }} &middot; {{ forloop.index }}/{{ g.photos.size }}">
      <img src="{{ '/assets/img/photography/' | append: p.thumb | relative_url }}"
           alt="{{ p.alt }}" width="{{ p.w }}" height="{{ p.h }}" loading="lazy" decoding="async">
    </a>
  </figure>
  {% endfor %}
</div>
{% endfor %}
{% endfor %}

<div class="lightbox" id="lightbox">
  <span class="lightbox-close" aria-label="Close">&times;</span>
  <button class="lightbox-nav lightbox-prev" type="button" aria-label="Previous">&#8249;</button>
  <img class="lightbox-img" id="lightbox-img" alt="">
  <button class="lightbox-nav lightbox-next" type="button" aria-label="Next">&#8250;</button>
  <p class="lightbox-caption" id="lightbox-caption"></p>
</div>
