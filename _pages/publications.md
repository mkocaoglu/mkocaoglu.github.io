---
layout: single
title: Publications
permalink: /publications/
---

<style>
.pub-container {
  display: flex;
  margin-bottom: 1.5em;
}
.pub-number {
  flex: 0 0 2.5em; /* Fixed width for numbers */
  text-align: right;
  padding-right: 1em;
}
.pub-content {
  flex: 1;
}
</style>

## Machine Learning / AI
{% assign counter = 1 %}
{% for pub in site.data.publications %}
{% if pub.paper_type == "ML" %}
<div class="pub-container">
  <div class="pub-number">[{{counter}}]</div>
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em>, {{ pub.year }}<br>
  {% if pub.awards %}
  <span class="awards">
    {% for award in pub.awards %}
    <span class="award">🏆 {{ award }}</span>
    {% endfor %}
  </span><br>
  {% endif %}
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  {% if pub.code %}<a href="{{ pub.code }}">[Code]</a>{% endif %}
  </div>
</div>
{% assign counter = counter | plus: 1 %}
{% endif %}
{% endfor %}

## Workshops
{% assign counter = 1 %}
{% for pub in site.data.publications %}
{% if pub.paper_type == "ML-Workshop" %}
<div class="pub-container">
  <div class="pub-number">[{{counter}}]</div>
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em>, {{ pub.year }}<br>
  {% if pub.awards %}
  <span class="awards">
    {% for award in pub.awards %}
    <span class="award">🏆 {{ award }}</span>
    {% endfor %}
  </span><br>
  {% endif %}
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  {% if pub.code %}<a href="{{ pub.code }}">[Code]</a>{% endif %}
  </div>
</div>
{% assign counter = counter | plus: 1 %}
{% endif %}
{% endfor %}
 
## Communications

### Journals

{% assign counter = 1 %}
{% for pub in site.data.publications %}
{% if pub.paper_type == "Communications-J" %}
<div class="pub-container">
  <div class="pub-number">[{{counter}}]</div>
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em>, {{ pub.year }}<br>
  {% if pub.awards %}
  <span class="awards">
    {% for award in pub.awards %}
    <span class="award">🏆 {{ award }}</span>
    {% endfor %}
  </span><br>
  {% endif %}
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  {% if pub.code %}<a href="{{ pub.code }}">[Code]</a>{% endif %}
  </div>
</div>
  {% assign counter = counter | plus: 1 %} 
{% endif %}
{% endfor %}

### Conferences

{% assign counter = 1 %}
{% for pub in site.data.publications %}
{% if pub.paper_type == "Communications-C" %}
<div class="pub-container">
  <div class="pub-number">[{{counter}}]</div>
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em>, {{ pub.year }}<br>
  {% if pub.awards %}
  <span class="awards">
    {% for award in pub.awards %}
    <span class="award">🏆 {{ award }}</span>
    {% endfor %}
  </span><br>
  {% endif %}
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  {% if pub.code %}<a href="{{ pub.code }}">[Code]</a>{% endif %}
  </div>
</div>
  {% assign counter = counter | plus: 1 %} 
{% endif %}
{% endfor %}

## PhD Thesis
{% for pub in site.data.publications %}
{% if pub.paper_type == "Thesis-PhD" %}
<div class="pub-container">
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em> <br> 
  {{ pub.location }}, {{ pub.year }}<br>
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  </div>
</div>
{% endif %}
{% endfor %}

## M. Sc. Thesis
{% for pub in site.data.publications %}
{% if pub.paper_type == "Thesis-MSc" %}
<div class="pub-container">
  <div class="pub-content">
  <strong>{{ pub.title }}</strong><br>
  {{ pub.authors | join: ", " }}<br>
  <em>{{ pub.venue }}</em> <br> 
  {{ pub.location }}, {{ pub.year }}<br>
  {% if pub.pdf %}<a href="{{ pub.pdf }}">[PDF]</a>{% endif %}
  </div>
</div>
{% endif %}
{% endfor %}