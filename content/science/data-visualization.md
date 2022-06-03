---
title: Data Visualization
date: 2022-01-01T18:24:31-05:00
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

Lately I've been experimenting with data visualization using Python and Matplotlib. I also recently read Rachel Carson's classic book, _The Sea Around Us,_ which inspired me to try visualizing the tides. This page is a collection of some of my experiments. I'll update this page whenever I finish a new visualization. Data from https://tidesandcurrents.noaa.gov unless otherwise noted.

<img class="centered" src="/img/TideSound-web.jpg" width=95%></img>
<br/>
This is a very basic visualization---just the water levels in Alameda, CA during November of 2021. This experiment had an interesting spinoff---I wrote a software instrument which synthesizes the same waveform at audio frequencies, which you can learn more about <a href="/tide-sound/">here.</a>
<br/>
<br/>

<img class="centered" src="/img/TideProfile_truncated-web.png" width=50%></img>
<br/>
This is a graph showing the relative heights of the tides in different locations. Each line represents a point in time. The largest tide height in any location at a given time is subtracted from all the other tide heights at that time, and they're then multiplied by a scaling factor to make the differences more visible.
<br/>
<br/>


<div style="margin: 0 auto; display: table;">
	<video controls class = "centered" src="/TideProfileVideo.mp4" align="center" width=100%></video>
</div>
	<br/>
	This video was an attempt to overcome one problem with the previous graph, namely its extreme height. Each image in the video shows a single point in time using the methodology described above. The indicator in the upper-left-hand corner is based off of the average height of all the tides at that time, to give an idea of when the tide is going in and out.
	<br/>
<br/>

<div style="margin: 0 auto; display: table;">
	<video controls class = "centered" src="/SolarSystemEscape.mp4" align="center" width=100%></video>
</div>
<br/>
This is a data visualization showing the courses of the five space vehicles currently heading away from the Solar System, never to return---Pioneer 10, Pioneer 11, Voyager 1, Voyager 2, and New Horizons.
<br/>
Tan = Pioneer 10, launched in 1972 to visit Jupiter. Contact lost in 2003 due to exhaustion of the onboard power supply, indicated in this video by the line turning gray.
<br/>
Reddish-brown = Pioneer 11, launched in 1973 to visit Jupiter and Saturn. Contact lost in 1995. You can clearly see each planetary encounter by watching the line abruptly change direction.
<br/>
Light yellow = Voyager 1, launched in 1977 to study Jupiter and Saturn (and their moons) in more detail. Currently the most distant human-made object from Earth.
<br/>
Dark yellow = Voyager 2, launched in 1977 to study all four giant planets (Jupiter, Saturn, Uranus, and Neptune.)
<br/>
Blue = New Horizons, launched in 2006 to study Pluto.
<br/>
Data credit: Natalia Papitashvili, <a href=' https://cdaweb.gsfc.nasa.gov/' target=blank>NASA Goddard Space Flight Center Space Physics Data Facility</a>
