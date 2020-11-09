---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true

---

{% include base_path %}

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
