---
title: "Protokolle"
---
<ul>
{% for post in site.posts %}{%if post.categories contains "protokoll" %} 
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{%endif%}
{% endfor %}
</ul>
