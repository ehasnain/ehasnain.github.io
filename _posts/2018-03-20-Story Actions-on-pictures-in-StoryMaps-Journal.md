---
layout: post
title:  "Story Actions on pictures"
excerpt: "The StoryMaps Journal editor does not support Story Actions on image files. However, it can be done by using some basic HTML tricks."
date:   2018-03-20 06:48:01 +0100
categories: storymaps
image: "/images/storymaps/Capture005.PNG"
---

The steps to be followed are listed below:

1. Create a desired Story Action on any arbitrary text as it is usually done. <br>

<span class="image center" style= "text-align:left;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture001.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>
<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture002.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>


2. Go to the ‘source code’ mode by clicking on the button left of the maximize button on the top left corner in the Edit Section. This would show the HTML source code of the section. <br>

<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture003.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>

3. Look for the text on which Story Action has been added. Copy the `<a>…</a>` tag around the text. <br>

<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture004.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>

4. Paste it around the `<img … />` tag of the image to which Story Action is desired. Delete the text on which the Story Action was originally added. Click on save when done. <br>
<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture005.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>

*Here is an example demonstrating the above trick:* [Supervised Theses at Esri Germany](http://esri-de-edu.maps.arcgis.com/apps/MapJournal/index.html?appid=2e8c944f3e424adcbf8e3db42a7e4114)