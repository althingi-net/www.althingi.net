---
layout: home
title: Um althingi.net
---

*Althingi.net* hýsir og fjallar um ýmsan hugbúnað sem nýtir gögn Alþingis á einhvern hátt.

Hugbúnaðurinn sem fjallað er um er jafnan ætlaður notendum, ýmist almenningi eða ákveðnum hópum, en vefurinn *althingi.net* sjálfur er fyrst og fremst hugsaður fyrir tæknifólk sem þróar slíkan hugbúnað.

# Verkefni

{% for project in site.projects %}
<a href="{{ project.url }}">{{ project.title }}</a>: {{ project.short-description }}
{% endfor %}

