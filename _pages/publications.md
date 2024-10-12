---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find this work on my [Google Scholar profile](https://scholar.google.com/citations?user=ST_EM7wAAAAJ&hl=en&oi=ao)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
