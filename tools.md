---
layout: page
title: Tools
permalink: /tools/
---

Tools and writeups that I've found useful over the course of my career:

{% for item in site.data.tools %}
	<a href="{{item.link}}" target=_blank>{{item.name}}</a>
{% endfor %}
