---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research is this. 

<br>

{% assign items = site.research | sort: "date" | reverse %}
{% for post in items %}
<h2>{{ post.title }}</h2>
{{ post.content }}
<hr>
{% endfor %}
