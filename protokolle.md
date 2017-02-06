---
layout: default
title: Protokolle
---
{% raw %}
{% for post in site.posts %}
  {% if post.categories contains 'protokoll' %}
	<div class="post">
		<h3 class="title"><a href="{{ post.url }}">{{ post.title }}</a></h3>
		<div class="entry">
			{{ post.content | strip_html | truncatewords: 100 }}
		</div>
	</div>
  {% endif %}
{% endfor %}
{% endraw %}
