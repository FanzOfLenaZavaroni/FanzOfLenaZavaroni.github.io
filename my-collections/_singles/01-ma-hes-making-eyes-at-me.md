---
layout: discography
year: 1974
title: Ma! (He's Making Eyes At Me)
subtitle: Single
description: Ma! (He's Making Eyes At Me) is the first single released by Lena Zavaroni and it was released shortly after her third appearance on Opportunity Knocks.
image: /assets/images/singles/musical-note.png
categories: [Discography, Singles]
---

<div id="player1"></div>
<div id="player2"></div>

Ma! (He's Making Eyes At Me) is the first single released by Lena Zavaroni and it was released shortly after her third appearance on Opportunity Knocks.

It was released in various countries with various cover images and a version was released in Japan in which Lena sang it in Japanese, in interviews Lena confirmed that she had learned the song in Japanese phonetically. The B-side of the Japanese release was &quot;(You've Got) Personality&quot; which would become Lena's second international single.

<table>
<tr><th>Artist:</th><td>Lena Zavaroni</td></tr>
<tr class="split"><th>A side:</th><td>Ma! (He's Making Eyes At Me)</td></tr>
<tr><th>Composer:</th><td>Conrad, Clare</td></tr>
<tr><th>Producer:</th><td>Tommy Scott</td></tr>
<tr><th>Arranger:</th><td>Tom Parker</td></tr>
<tr class="split"><th>B side:</th><td>Rock-A-Bye Your Baby With A Dixie Melody</td></tr>
<tr><th>Composer:</th><td>Lewis, Young, Schwartz</td></tr>
<tr><th>Producer:</th><td>Tommy Scott</td></tr>
<tr><th>Arranger:</th><td>Tom Parker</td></tr>
<tr class="split"><th>Label:</th><td>Philips - 6006 367</td></tr>
<tr><th>Format:</th><td>7" Vinyl, 45 Single</td></tr>
<tr><th>Country:</th><td>England</td></tr>
<tr><th>Released:</th><td>25 January 1974</td></tr>
</table>

### Related Website
* [45Cat](http://www.45cat.com/record/6006367)

<style>
#player1 {width:367.5px; height:277px;}
#player2 {width:367.5px; height:277px;}
.split {border-top: solid 5px #4B90B1;}
</style>

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
            videoId: 'DzqcGLl8rMg',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '360',
            width: '480',
            videoId: 'Yc1h6cDkc8M',
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

