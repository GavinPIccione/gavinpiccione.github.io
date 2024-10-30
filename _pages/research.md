---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

{% for post in site.research %}
  {% include single-portfolio.html type="grid" %}
{% endfor %}
