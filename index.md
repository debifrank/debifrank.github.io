---
layout: page
title: Home
permalink: /home/
---

{% if site.posts.size > 0 %}
    {% for post in site.posts %}
		## [{{ post.title }}]({{ post.url }})
		{{ post.excerpt }}
	{% endfor %}
{% endif %}
