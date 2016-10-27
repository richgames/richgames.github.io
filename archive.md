---
layout: page
title: Archive 
---

Blog
----

{% for post in site.posts %}
{% if post.layout == 'post' %}
  * {{ post.date | date_to_string}} &raquo; [ {{ post.title}} ]({{ post.url }})
{% endif %}
{% endfor %}

Product
-------

{% for post in site.posts %}
{% if post.layout == 'product' %}
  * {{ post.date | date_to_string}} &raquo; [ {{ post.title}} ]({{ post.url }})
{% endif %}
{% endfor %}
