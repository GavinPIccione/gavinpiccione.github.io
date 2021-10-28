---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find this work on my <u><a href="https://scholar.google.com/citations?user=DR4WkTsAAAAJ&hl=en&oi=ao"> Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
