---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true
images:
- image_path: /images/the_stare_by_mkocaoglu-d2t319i.jpg
  title: The Stare
  
- image_path: /images/feeling_loved_by_mkocaoglu-d811qia.jpg
  title: Feeling Loved
  
- image_path: /images/half_by_mkocaoglu-d9bf786.jpg
  title: Half
  
- image_path: /images/horizon_by_mkocaoglu-d8o6t05.jpg
  title: Horizon
---

{% include base_path %}

<p float="left">
    {% for image in page.images %}
    <img src="{{ image.image_path }}" alt="{{ image.title}}" width="200"/>
  {% endfor %}
</p>
