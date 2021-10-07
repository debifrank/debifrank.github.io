---
layout: page
title: Home
permalink: /home/
---

{% include home.html %}
{% if site.posts.size > 0 %}
    {% for post in site.posts %}
		## [{{ post.title }}]({{ post.url }})
		{{ post.excerpt }}
	{% endfor %}
{% endif %}
