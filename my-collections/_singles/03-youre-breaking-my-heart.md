---
layout: discography
year: 28 February 1975
title: You're Breaking My Heart
b-side: You're Never Too Old
description: This is the 11th single by Lena Zavaroni.
categories: [Discography, Singles]
---

<div id="player1"></div>
<div id="player2"></div>

<table>
<tr><th>Artist:</th><td>Lena Zavaroni</td></tr>
<tr class="split"><th>A side:</th><td>You're Breaking My Heart</td></tr>
<tr><th>Composer:</th><td>Genara, Skylar</td></tr>
<tr><th>Producer:</th><td>John Franz</td></tr>
<tr><th>Arranger:</th><td>Peter Knight</td></tr>
<tr class="split"><th>B side:</th><td>You're Never Too Old</td></tr>
<tr><th>Composer:</th><td>Franz, Blackburn</td></tr>
<tr><th>Producer:</th><td>John Franz</td></tr>
<tr><th>Arranger:</th><td>Peter Knight</td></tr>
<tr class="split"><th>Label:</th><td>Philips - 6006 445</td></tr>
<tr><th>Format:</th><td>7" Vinyl, 45 Single</td></tr>
<tr><th>Country:</th><td>England</td></tr>
<tr><th>Released:</th><td>28 February 1975</td></tr>
</table>

<style>
#player1 {width:367.5px; height:277px;}
#player2 {width:367.5px; height:277px;}
.split {border-top: solid 5px #4B90B1;}
</style>

### Related Website
* [45Cat](http://www.45cat.com/record/6006445)

<script>
    var tag = document.createElement('script');
    tag.src = "//www.youtube.com/iframe_api";
    var firstScriptTag = document.getElementsByTagName('script')[0];
    firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

    var player;
    function onYouTubeIframeAPIReady() {
        player1 = new YT.Player('player1', {
            height: '360',
            width: '480',
            videoId: 'm8YQryTU7yA',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '360',
            width: '480',
            videoId: 'KoviPL00AFY',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
    }

    function onPlayerStateChange(event) {
        if (event.data == YT.PlayerState.PLAYING) {
            stopVideo(event.target.a.id);
        }
    }

    function stopVideo(player_id) {
        if (player_id == "player1") {
            player2.stopVideo();
        } else if (player_id == "player2") {
            player1.stopVideo();
        }
    }
</script>

