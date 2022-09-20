---
layout: default

mathjax: true

permalink: "/on/"

title: "On ... and other ramblings"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
