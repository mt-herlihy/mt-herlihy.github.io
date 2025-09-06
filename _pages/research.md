---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are in American political institutions, particularly judicial selection and the separation of powers. In my work, I look to answer questions about (1) the dynamics that influence federal confirmations, (2) how the public thinks about judicial nominees and judicial elections, and (3) how courts impact the policy success of the executive and legislative branches. My dissertation project, <em>For the Record: Venue and Communication Strategies in Lower Court Judicial Confirmations</em>—funded by a Law and Science Dissertation Grant from the National Science Foundation—theorizes about strategic behavior and communication between senators and judicial nominees, particularly in the wake of the 2013 Senate rules change known as the “nuclear option.” 

<br>

{% assign items = site.research | sort: "date" | reverse %}
{% for post in items %}
<h2>{{ post.title }}</h2>
{{ post.content }}
<hr>
{% endfor %}
