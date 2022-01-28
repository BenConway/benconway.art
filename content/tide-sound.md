---
title: 
date: 2022-01-27T14:57:46-08:00
layout: page
draft: false
---

<style type="text/css" rel="stylesheet">
body{background: #666666;}
IMG.centered {
display: block;
margin-left: auto;
margin-right: auto}
</style>

<img class="centered" src="/img/TideSound-web.jpg" width=95%></img>
<br/>

<div style="margin: 0 auto; display: table;">
	<audio controls class = "centered" src="/Tides.wav" align="center"></audio>
</div>
	<br/>

I've been doing some more experiments with unusual sound sources! This one grew out of a data visualization project---graphing the tides in San Francisco Bay. I realized that the tide graph had an interesting waveform to it, and I wondered what it would sound like played back at audio frequencies. The NOAA website has lists of the harmonic constituents that make up the tide graphs for a particular location. (Quick explanation if you don't know what those are---any complex waveform can be represented as a bunch of simpler waveforms added together. Harmonic constituents are the simple waveforms that can be added together to produce a tide graph.) I wrote a Csound instrument that synthesizes tide waveforms based on 11 of the most significant harmonic constituents for Alameda. The result is the sound heard here (it's pretty quiet, so you may need to turn up your volume to hear it.) I also wrote a song based off of it, which I'm going to release on my next album.

The graph shows the tides in Alameda, CA in November 2021, based on data from https://tidesandcurrents.noaa.gov/map/index.html?id=9414750.

Harmonic constituent data from https://tidesandcurrents.noaa.gov/harcon.html?id=9414750.
