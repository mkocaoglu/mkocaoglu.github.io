---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true
images:
- image_path: /images/the_stare_by_mkocaoglu_d2t319i.jpg
  title: The Stare
  
- image_path: /images/feeling_loved_by_mkocaoglu_d811qia.jpg
  title: Feeling Loved
  
- image_path: /images/half_by_mkocaoglu_d9bf786.jpg
  title: Half
  
- image_path: /images/horizon_by_mkocaoglu_d8o6t05.jpg
  title: Horizon
---

{% include base_path %}

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
