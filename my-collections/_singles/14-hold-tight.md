---
layout: discography
year: 
title: Hold Tight (Want Some Sea Food, Mama)
maintitle: Hold Tight (Want Some Sea Food, Mama)
subtitle: Single
description: This is the 14th single by Lena Zavaroni
media: 7" Vinyl, 45 Single
post_description: 
image: /assets/images/singles/
categories: [Discography, Singles]
published: false
---

<main class="Main-Default">
<article>
<div class="row">
<div class="col s12 m8 offset-m2 l6 offset-l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-music" aria-hidden="true"></i> Hold Tight (Want Some Sea Food, Mama)</h4>
<strong>18 February 1977</strong>
<br/><br/>
<p>The B-Side of this single is &quot;Ain't She Sweet&quot;.</p>
<br/>
<p>Both tracks are also on her final album <a href="https://fanzoflenazavaroni.github.io/television/1977/the-musical-time-machine.html">Hold Tight, It's Lena</a>.</p>
<br/>
<p>All the tracks on this single and the related album were preformed by Lena on series 3 of her TV Show "Lena".</p>
</div></div></div></div>

<div class="row">
<div class="col s12 m8 offset-m2 l6 offset-l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-info" aria-hidden="true"></i> Details</h4>
<ul>
  <li><b>Artist:</b> Lena Zavaroni</li>
  <li><b>A side:</b> Hold Tight (Want Some Sea Food, Mama)</li>
  <li><b>B side:</b> Ain't She Sweet</li>
  <li><b>Label:</b> BBC</li>
  <li><b>Country:</b> England</li>
  <li><b>Catalogue:</b> RESL 117</li>
  <li><b>Released:</b> 11 Jun 1982</li>
</ul>
</div>
<div class="card-action flow-text">
<a href="http://www.45cat.com/record/resl117">45Cat</a>
</div></div></div></div>

<div class="row">
<div class="col s12 m4 offset-m2 l3 offset-l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-youtube" aria-hidden="true"></i> YouTube</h4>
<div class="video-container">
<div id="player1"></div>
</div></div>
<div class="card-action">
<p>Hold Tight (Want Some Sea Food, Mama)</p>
</div></div></div>

<div class="col s12 m4 l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-youtube" aria-hidden="true"></i> YouTube</h4>
<div class="video-container">
<div id="player2"></div>
</div></div>
<div class="card-action">
<p>Ain't She Sweet</p>
</div></div></div></div>
</article>
</main>

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
            videoId: 'g0dTaMVaIOY',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '360',
            width: '480',
            videoId: 'CUL1pzfA1TE',
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

<!-- Scripts -->
<script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
<script src="/materialize/js/materialize.min.js"></script>
<script src="/materialize/js/init.js"></script>
</body>
</html>
