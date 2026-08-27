---
layout: page
title: Photography
permalink: /photography/
description: Astrophotography and night sky captures.
nav: true
nav_order: 3
---

<div class="photo-masonry">
  {% for photo in site.data.photos %}
  <figure>
    <a href="{{ '/assets/img/photography/' | append: photo.file | relative_url }}" class="lightbox-trigger">
      <img src="{{ '/assets/img/photography/' | append: photo.file | relative_url }}" alt="{{ photo.alt }}" loading="lazy">
    </a>
  </figure>
  {% endfor %}
</div>

<div class="lightbox" id="lightbox">
  <span class="lightbox-close">&times;</span>
  <img class="lightbox-img" id="lightbox-img" alt="">
</div>
