---
layout: page
title: Orginalritningar
excerpt: "Orginalritningar från när huset byggdes, 1903-1905"
search_omit: true
---

Orginalritningar från 1903 - 1905 över fastigheten Morkullan 4 som ägs av BRF Morkullan 4.

Är du ute efter en fullskalig ritning och vet vad den heter eller vilken typ och vy den ska innehåll, kan du också gå <a href="https://github.com/karttur/morkullan4/tree/gh-pages/ritningar/doc/full">direkt till arkivet som innehåller alla ritningar (GitHub sida)</a>.

<ul class="post-list">
{% for post in site.categories.ritningar %}
  {% if post.perspektiv == "orginalritning" %}
    <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}  <span class="excerpt"> {{ post.ritningsnummer }}, Skala 1 : {{ post.scale }}</span></a></article></li>
  {% endif %}
{% endfor %}
</ul>
