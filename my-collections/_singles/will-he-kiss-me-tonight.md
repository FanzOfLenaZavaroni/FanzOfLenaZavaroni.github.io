---
layout: post
year: November 1980
title: Will He Kiss Me Tonight
b-side: 
---

<div id="player1"></div>
<div id="player2"></div>

<table>
<tr><th>Artist:</th><td>Lena Zavaroni</td></tr>
<tr class="split"><th>A side:</th><td>Will He Kiss Me Tonight</td></tr>
<tr><th>Composer:</th><td>The Dolly Mixture</td></tr>
<tr><th>Producer:</th><td>David Goodman</td></tr>
<tr><th>Arranger:</th><td>David Goodman</td></tr>
<tr class="split"><th>B side:</th><td>Dream Come True</td></tr>
<tr><th>Composer:</th><td>The Dolly Mixture</td></tr>
<tr><th>Producer:</th><td>David Goodman</td></tr>
<tr><th>Arranger:</th><td>David Goodman</td></tr>
<tr class="split"><th>Label:</th><td>Galaxy - GY 177</td></tr>
<tr><th>Format:</th><td>7" Vinyl, 45 Single</td></tr>
<tr><th>Country:</th><td>England</td></tr>
<tr><th>Released:</th><td>November 1980</td></tr>
</table>

**Related Website:**
<span class="post-categories">[45Cat](http://www.45cat.com/record/gy177)</span>

<style>
#player1 {width:367.5px; height:277px;}
#player2 {width:367.5px; height:277px;}
.split {border-top: solid 5px #f00;}
</style>

<script>
    var tag = document.createElement('script');
    tag.src = "//www.youtube.com/iframe_api";
    var firstScriptTag = document.getElementsByTagName('script')[0];
    firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

    var player;
    function onYouTubeIframeAPIReady() {
        player1 = new YT.Player('player1', {
            height: '277',
            width: '320',
            videoId: 'LlOxtPgnyHw',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '277',
            width: '320',
            videoId: 'JOlnumOA1NU',
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

