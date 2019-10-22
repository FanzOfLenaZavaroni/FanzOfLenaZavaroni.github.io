---
layout: page
title: Updates
description: Latest news, updates & changes
---

{% for post in site.categories.Updates %}
 <li><span>{{ post.date | date_to_string }}</span> - <a href="{{ post.url }}">{{ post.subtitle }}</a></li>
{% endfor %}

<style>
.post-header {display: none;}
.post-content:before {font-size: 42px; content: "Latest news, updates & changes.";}
</style>

