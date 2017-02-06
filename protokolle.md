---
title: "Protokolle"
---
{% for post in site.posts %}
{%if post.categories contains "protokoll" %} 
- <a href="{{ post.url }}">{{ post.title }}</a>
{%endif%}
{% endfor %}
