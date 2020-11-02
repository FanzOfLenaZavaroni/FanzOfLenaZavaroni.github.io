---
layout: default
title: Discography
maintitle: Discography
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

<h1>Spoken Word</h1>
{% for spoken-word in site.spoken-word %}
  <h2><a href="{{ spoken-word.url }}">{{ spoken-word.title }} ({{ spoken-word.year }})</a></h2>
{% endfor %}

<h1>Tribute Songs</h1>
{% for tribute-songs in site.tribute-songs %}
  <h2><a href="{{ tribute-songs.url }}">{{ tribute-songs.title }} ({{ tribute-songs.year }})</a></h2>
{% endfor %}
