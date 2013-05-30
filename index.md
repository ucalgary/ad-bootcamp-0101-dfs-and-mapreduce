---
layout: presentation
title: "AD Bootcamp Session 101: DFS and MapReduce"
---

{% for post in site.posts reversed %}
  {% include slide.html %}
{% endfor %}
{% unless site.simple-slideshow %}
{% if site.overview %}
<div id="overview" class="step" {% for attr in site.overview-data %} data-{{attr[0]}}="{{attr[1]}}"{% endfor %}></div>
{% endif %}
{% endunless %}