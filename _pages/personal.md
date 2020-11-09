---
layout: archive
title: "Personal"
permalink: /personal/
author_profile: true
images:
- image_path: /images/the_stare_by_mkocaoglu-d2t319i.jpg
  title: The Stare
  width: 300
  
- image_path: /images/feeling_loved_by_mkocaoglu-d811qia.jpg
  title: Feeling Loved
  width: 580
  
- image_path: /images/half_by_mkocaoglu-d9bf786.jpg
  title: Half
  width: 750
  
- image_path: /images/horizon_by_mkocaoglu-d8o6t05.jpg
  title: Horizon
  width: 750
---

{% include base_path %}

<p float="left">
    {% for image in page.images %}
    <img src="{{ image.image_path }}" alt="{{ image.title}}" width="{{ image.width}}"/>
    style="padding-left: 10px;padding-right: 10px; padding-bottom: 20px;"
  {% endfor %}
</p>

For more, please check out my [page](https://www.deviantart.com/mkocaoglu). 
