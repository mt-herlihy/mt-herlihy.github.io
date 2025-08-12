---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% for item in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
