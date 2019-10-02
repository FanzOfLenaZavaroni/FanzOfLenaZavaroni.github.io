---
layout: page
title: On This Day
---

{% for page in site.pages %}
  {% if page.categories contains 'On This Day' %}

[{{ page.title }} - {{page.subtitle}}]({{ page.url }})
  {% endif %}
{% endfor %}

