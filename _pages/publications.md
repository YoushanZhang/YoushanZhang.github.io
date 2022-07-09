---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


SCORN: Sinter Composition Optimization with Regressive Convolutional Neural Network

* Zhang, Y., Wieland, M., & Basran, P. S. (2022). Unsupervised Few Shot Key Frame Extraction for Cow Teat Videos. Data, 7(5), 68.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">[my Google Scholar profile](https://scholar.google.com/citations?user=47ItLM8AAAAJ&hl=en)</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
