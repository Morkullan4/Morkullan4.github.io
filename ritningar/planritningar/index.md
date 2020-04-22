---
layout: page
title: Planritningar
excerpt: "Planritningar"
search_omit: true
---

Planritningar över fastigheten Morkullan 4 som ägs av BRF Morkullan 4.

Är du ute efter en fullskalig ritning och vet vad den heter eller vilken typ och vy den ska innehåll, kan du också gå <a href="https://github.com/karttur/morkullan4/tree/gh-pages/ritningar/doc/full">direkt till arkivet som innehåller alla ritningar (GitHub sida)</a>.

<ul class="post-list">
{% for post in site.categories.ritningar %}
  {% if post.perspektiv == "planritning" %}
    <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}  <span class="excerpt"> {{ post.ritningsnummer }}, Skala 1 : {{ post.scale }}, Hus: {{ post.hus }}, Plan: {{ post.plan }}</span></a></article></li>
  {% endif %}
{% endfor %}
</ul>
