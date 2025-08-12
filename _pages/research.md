---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% for post in site.research reversed %}
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
{{ post.content | markdownify }}
<hr>
{% endfor %}

