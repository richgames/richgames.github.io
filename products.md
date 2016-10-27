---
layout: page
title: Products
---

{% for post in site.posts %}
  {% if post.tags contains 'available' %}
  <p class="message">
     {{post.title}}
     <a href="{{ post.url }}"><img src="/assets/{{ post.img }}"></a>
  </p>
  {% endif %}
{% endfor %}

Check out more hand-crafted games on [Etsy](https://www.etsy.com/shop/RichGames/).
