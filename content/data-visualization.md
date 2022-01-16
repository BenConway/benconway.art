---
title: Data Visualization
date: 2022-01-01T18:24:31-05:00
layout: single
draft: true
---
<style type="text/css" rel="stylesheet">
body{background: #666666;}
IMG.centered {
display: block;
margin-left: auto;
margin-right: auto}
</style>

Recently I've started teaching myself data visualization with Jupyter Notebook and Matplotlib. I was inspired to try visualizing the tides after reading Rachel Carson's classic book, _The Sea Around Us._ This page is a collection of some of my experiments. Data from [SITE] unless otherwise noted.

<img class="centered" src="/SF-RWC-Alameda-tides.png" width=800></img>
<br/>
The most basic chart: a line graph. This is a graph of the tides in San Francisco (gray), Alameda (blue), and Redwood City (red) between November 12 and November 13, 2021.

<img class="centered" src="/3DTides_1.png" width=800></img>
<br/>
<img class="centered" src="/3DTides_2.png" width=800></img>
<br/>
These are some stills from an interactive 3D chart of the tides in the above locations plus Richmond. You can see how the water level in each location as compared to other locations varies over time.

<img class="centered" src="/NormalizedTideChart.png" width=800></img>
<br/>
<img class="centered" src="/NormalizedTidesA.png" width=800></img>
<br/>
<img class="centered" src="/NormalizedTidesB.png" width=800></img>
<br/>
<img class="centered" src="/NormalizedTidesC.png" width=800></img>
<br/>
This chart compares the tide height at different locations, by dividing the tide height at each location by the largest tide height at any location at the same time.

<img class="centered" src="/TideProfileTest.png" width=800></img>
This is another method of comparing tide height across locations. Each line represents a time, starting at midnight on November 12 and running in 6-minute increments until midnight on November 13. [VERIFY.] Each point on a line shows the tide height at each location (L-R: Richmond, San Francisco, Alameda, and Redwood City)[VERIFY] with the largest tide height at that time subtracted from it.
<br/>
