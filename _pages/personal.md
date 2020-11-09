---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true
images:
- image_path: /images/the_stare_by_mkocaoglu_d2t319i.jpg
  title: The Stare
---

{% include base_path %}

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
