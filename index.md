---
excerpt: "Wo Ton zu Leben erwacht: Einzigartige Figuren, handgeformt mit Leidenschaft."
title: "Ingride - Kreativgeist in Ton"
layout: collection
header:
  overlay_image: /assets/img/Header06.png
  #overlay_filter: rgba(190, 190, 190, 0.3)
  #image: /assets/img/Header02.png
  #teaser: /assets/img/Header02.png
---

{% assign ordered_content = site.combined_content | sort:"order" %}

{% for main_content in ordered_content %}
  <p>{{ main_content.content | markdownify }}</p>
{% endfor %}