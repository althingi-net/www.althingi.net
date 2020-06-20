---
layout: home
title: Um althingi.net
---

*Althingi.net* er miðlæg gátt fyrir hugbúnað og vefi sem með einhverjum hætti nýta gögn Alþingis.

# Verkefni

{% for project in site.projects %}
<a href="{{ project.url }}">{{ project.title }}</a>: {{ project.short-description }}
{% endfor %}

