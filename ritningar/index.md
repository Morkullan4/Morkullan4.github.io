---
layout: page
title: Ritningar
excerpt: "Ritningar"
search_omit: true
---

Här kan du hitta olika ritningar över fastigheten Morkullan 4 som ägs av BRF Morkullan 4.

Är du ute efter en fullskalig ritning och vet vad den heter eller vilken typ och vy den ska innehåll, kan du också gå <a href="https://github.com/karttur/morkullan4/tree/gh-pages/ritningar/doc/full">direkt till arkivet som innehåller alla ritningar (GitHub sida)</a>. Längre ned på sidan finns också länkar till alla ritningar som finns tillgängliga här.

I den kortare listan över tematiska ritnignar kan du klicka dig till ritnigar från en viss period och med ett visst innehåll.

### Ritningar sorterade efter ålder och tema

- <a href="./planritningar/index.html">Planritningar (1986)</a>
- <a href="./fasad/index.html">Fasadritningar (1986)</a>
- <a href="./vvs/index.html">VVS ritningar (1986)</a>
- <a href="./sektioner/index.html">Sektioner (1986)</a>
- <a href="./bjaelklag/index.html">Bjälklag (1986)</a>
- <a href="./detaljer/index.html">Detaljritningar (1986)</a>
- <a href="./hiss/index.html">Hissritningar (1986)</a>
- <a href="./orginal/index.html">Orginalritningar (1903-1905)</a>

### Samtliga tillgängliga ritningar

<ul class="post-list">
{% for post in site.categories.ritningar %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}  <span class="excerpt"> {{ post.ritningsnummer }}, Skala 1 : {{ post.scale }}</span></a></article></li>
{% endfor %}
</ul>
