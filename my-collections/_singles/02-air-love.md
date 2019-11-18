---
layout: post
year: 1977
title: Air Love
b-side: Pinch Me Am I Dreaming
---






<main class="Main-Default">
<article>
<div class="row">
<div class="col s12 m8 offset-m2 l6 offset-l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-music" aria-hidden="true"></i> Air Love</h4>
<strong>18 February 1977</strong>
<br/><br/>
<p>The B-Side of this single is &quot;Pinch Me Am I Dreaming&quot;.</p>
<br/>
<p>Lena performed &quot;Air Love&quot; on <a href="https://fanzoflenazavaroni.github.io/television/1977/the-musical-time-machine.html">The Musical Time Machine</a> and on <a href="/television/hi-summer/hi-summer-07.html">Hi Summer - Episode 7</a>.</p>
<br/>
<p>Lena performed the B-side &quot;Pinch Me Am I Dreaming&quot; on <a href="/television/pebble-mill-at-one/pebble-mill-at-one1.html">Pebble Mill at One</a>, <a href="/television/hi-summer/hi-summer-04.html">Hi Summer - Episode 4</a> and the chorus of the song on <a href="/television/hi-summer/hi-summer-08.html">Hi Summer - Episode 8</a>.</p>
<br/>
<p>Both songs from this single were also released on her LP <a href="/discography/studio-albums/presenting-lena-zavaroni.html">Presenting Lena Zavaroni</a> and &quot;Air Love&quot; was also released on the compilation LP for the TV Series <a href="/discography/compilation-albums/o-profeta-Internacional.html">O Profeta</a>.</p>
</div></div></div></div>

<div class="row">
<div class="col s12 m8 offset-m2 l6 offset-l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-info" aria-hidden="true"></i> Details</h4>
<ul>
  <li><b>Artist:</b> Lena Zavaroni</li>
  <li><b>A side:</b> Air Love</li>
  <li><b>B side:</b> Pinch Me Am I Dreaming</li>
  <li><b>Label:</b> Galaxy</li>
  <li><b>Country:</b> England</li>
  <li><b>Catalogue:</b> GY 114</li>
  <li><b>Released:</b> 18 Feb 1977</li>
</ul>
</div>
<div class="card-action flow-text">
<a href="http://www.45cat.com/record/gy114">45Cat</a>
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
<p>Air Love</p>
</div></div></div>

<div class="col s12 m4 l3">
<div class="card">
<div class="card-content flow-text">
<h4><i class="fa fa-youtube" aria-hidden="true"></i> YouTube</h4>
<div class="video-container">
<div id="player2"></div>
</div></div>
<div class="card-action">
<p>Pinch Me Am I Dreaming</p>
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
            videoId: '2uWtecHKHRw',
            events: {
                'onStateChange': onPlayerStateChange
            }
        });
        player2 = new YT.Player('player2', {
            height: '360',
            width: '480',
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

<!-- Scripts -->
<script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
<script src="/materialize/js/materialize.min.js"></script>
<script src="/materialize/js/init.js"></script>
</body>
</html>
