---
layout: post
title:  "Story Actions on pictures in StoryMaps Journal"
date:   2018-03-20 06:48:01 +0100
categories: storymaps
---

The StoryMaps Journal editor does not support Story Actions on image files. However, it can be done by using some basic HTML tricks. <!--more-->

The steps to be followed are listed below:

1. Create a desired Story Action on any arbitrary text as it is usually done.
![Image 1]({{ "/assets/images/storymaps/Capture001.PNG" | absolute_url }}) ![Image 2]({{ "/assets/images/storymaps/Capture002.PNG" | absolute_url }})

2. Go to the ‘source code’ mode by clicking on the button left of the maximize button on the top left corner in the Edit Section. This would show the HTML source code of the section.
![Image 3]({{ "/assets/images/storymaps/Capture003.PNG" | absolute_url }})

3. Look for the text on which Story Action has been added. Copy the `<a>…</a>` tag around the text.
![Image 4]({{ "/assets/images/storymaps/Capture004.PNG" | absolute_url }})

4. Paste it around the `<img … />` tag of the image to which Story Action is desired. Delete the text on which the Story Action was originally added. Click on save when done.
![Image 5]({{ "/assets/images/storymaps/Capture005.PNG" | absolute_url }})

*Here is an example demonstrating the above trick:* [Supervised Theses at Esri Germany](http://esri-de-edu.maps.arcgis.com/apps/MapJournal/index.html?appid=2e8c944f3e424adcbf8e3db42a7e4114)