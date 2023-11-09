---
title: Mein Portfolio
permalink: /combined_content_page/
layout: collection
---

{% assign ordered_content = site.combined_content | sort:"order" %}

{% for main_content in ordered_content %}
  <p>{{ main_content.content | markdownify }}</p>
{% endfor %}