---
layout: default
title: "Explore"
---


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="The Journal" %}
{% endif %}
