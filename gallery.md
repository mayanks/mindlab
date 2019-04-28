---
layout: default
title:  "Gallery"
author: roma
categories: [ ]
image: assets/images/3.jpg
---

<h1>Gallery</h1>
<div class="gallery-container row">
  {% for image in site.gallery %}
    <a class="col-sm-3" href="{{ site.baseurl }}/assets/images/gallery/{{ image }}">
      <img src="{{ site.baseurl }}/assets/images/gallery/{{ image }}"/>
    </a>
  {% endfor %}
</div>
