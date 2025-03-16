---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
My research interests are centered broadly around questions related to i) the effects of climate change on polar and glaciated environments, and ii) the mobilization and concentration of trace metals in surface waters. Specifically, I use geochemical measurements of the rock record to describe the evolution of glaciers and ice sheets on decade to millennial timescales, as well as the impacts of changing ice conditions on local and global biogeochemical cycles. I integrate these novel datasets with geochemical and climate model outputs to help clarify the links between the atmosphere, hydrosphere, lithosphere, and cryosphere. 

In addition to ice-related projects, I am also interested in hydroclimate response to climate forcing, pollution in urban watersheds, and critical mineral formation in hydrothermal systems.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}