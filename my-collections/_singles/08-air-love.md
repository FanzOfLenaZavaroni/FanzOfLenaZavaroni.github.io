---
layout: discography
year: 1977
title: Air Love
subtitle: Single
b-side: Pinch Me Am I Dreaming
description: This is the 8th single by Lena Zavaroni.
categories: [Discography, Singles]
---

<table>
<tr><th>Artist:</th><td>Lena Zavaroni</td></tr>
<tr><th>A side:</th><td>Air Love</td></tr>
<tr><th>B side:</th><td>Pinch Me Am I Dreaming</td></tr>
<tr><th>Label:</th><td>Galaxy – GY 114</td></tr>
<tr><th>Format:</th><td>7" Vinyl, 45 Single</td></tr>
<tr><th>Country:</th><td>England</td></tr>
<tr><th>Released:</th><td>18 February 1977</td></tr>
</table>

Lena performed Air Love on [The Musical Time Machine](/bbc%20one/1977/02/15/the-musical-time-machine.html) and on [Hi Summer - Episode 7](/television/london%20weekend%20television/1977/08/28/hi-summer.html).

Lena performed the B-side Pinch Me Am I Dreaming on [Pebble Mill at One](), [Hi Summer - Episode 4](/television/london%20weekend%20television/1977/08/07/hi-summer.html) and the chorus of the song on [Hi Summer - Episode 8]()

Both songs from this single were also released on her album [Presenting Lena Zavaroni](/discography/albums/03-presenting-lena-zavaroni) and Air Love was also released on the compilation album for the TV Series [O Profeta]().

> <div class="responsive-video"><div id="player1"></div></div>

<cite>Air Love</cite>

> <div class="responsive-video"><div id="player2"></div></div>

<cite>Pinch Me Am I Dreaming</cite>

<script>
    var tag = document.createElement('script');
    tag.src = "//www.youtube.com/iframe_api";
    var firstScriptTag = document.getElementsByTagName('script')[0];
    firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

    var player;
    function onYouTubeIframeAPIReady() {
        player1 = new YT.Player('player1', {
            height: '480',
            width: '640',
            videoId: '2uWtecHKHRw',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '480',
            width: '640',
            videoId: 'XTaSIoMmddg',
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

**Related Website:**
<span class="post-categories">[45Cat](http://www.45cat.com/record/gy114)</span>
