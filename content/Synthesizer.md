---
title: 
date: 2025-05-13T08:41:54-07:00
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

<img class="centered" src="/img/IMG_9416.png" width=800></img>
<br/>

For the past few years, I've been working on a music synthesizer. I initially finished it in May of 2025, but then I wanted to add some more features. I started that in August of 2025, and (after dealing with a lot of unexpected issues, including redoing a bunch of the machine's internal electronics) I got it finished again in February of 2026. I imagine I'll end up reworking it again at some point.

I designed and built the entire thing myself. That means that the machine's really well-adapted to the type of music I like to make. The downside is that I have to fix any problems with it all by myself---there's nothing quite like it anywhere else in the world.

The synth can be used to play a melody over an optional background drone. Sometimes the melody notes clash with the drone, so I added a touch sensor to turn off the drone for short periods of time.

The keyboard only covers one octave, but the synth has a 3-octave range. One switch lowers the pitch an octave, while another raises it an octave. (The first version of the synth only had a 2-octave range, but I wanted more, so I added the other switch. The pitch-lowering switch on the first version also turned out to be hard to reach, so I added a new switch for that and repurposed the old pitch-lowering switch for something else.)

One knob on the synth is for selecting different sound waveforms. I derived most of these graphically from natural shapes (see <a href='/wavetables/'>here</a> for more details.) I also wanted to add a white-noise-like sound to the new version, which proved to be a challenge as the whole point of white noise is that it's randomly-varying. You can't just make a sound like that by playing a short sample repeatedly, the way the synth's other sounds work. I happened to notice, however, that when I had the waveform knob right between two positions, the system would flip randomly between the two waveform settings. This sounded _almost_ the way I wanted. So I ended up adding a setting that approximates white noise by playing a complex waveform and randomly changing the frequency.

The other knob controls the synth's tremolo effect, varying the volume at a few different speeds ranging from 8 times a second to once every 16 seconds. The faster speeds are good for creating a sort of shimmering sound, the slower speeds are good for gradually-shifting ambient sounds,

The case is made from wood, which I had laser-cut by <a href='https://ponoko.com'>Ponoko.</a> The current version of the synth uses an <a href='https://www.adafruit.com/product/3677'>Adafruit ItsyBitsy</a> microcontroller. The sound synthesis is handled by the <a href='https://sensorium.github.io/Mozzi/doc/html/index.html'>Mozzi</a> Arduino library.


<br/>
<br/>
Original synthesizer:
<br/>
<div style="margin: 0 auto; display: table;">
	<video controls class = "centered" src="/Synth-finish.mp4" align="left" width=70%></video>
</div>
<br/><br/>

Upgraded synthesizer:
<br/>
<div style="margin: 0 auto; display: table;">
	<video controls class = "centered" src="/0001-2604.mp4" align="left" width=70%></video>
</div>
