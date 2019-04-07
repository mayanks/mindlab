---
layout: page
title:  "Gallery"
author: sal
categories: [ ]
image: assets/images/3.jpg
---

<div class="gallery-container">
  {% for image in site.gallery %}
    <a href="{{ site.baseurl }}/assets/images/gallery/{{ image }}">
      <img src="{{ site.baseurl }}/assets/images/gallery/{{ image }}"/>
    </a>
  {% endfor %}
</div>
