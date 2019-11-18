---
layout: default
title: Discography
---
<h1>Discography</h1>

<h1>Albums</h1>
{% for albums in site.albums %}
  <h2><a href="{{ albums.url }}">{{ albums.title }} ({{ albums.year }})</a></h2>
{% endfor %}

<h1>Singles</h1>
{% for singles in site.singles %}
  <h2><a href="{{ singles.url }}">{{ singles.title }} ({{ singles.year }})</a></h2>
{% endfor %}

