---
layout: post
title:  "Dropdown menu in StoryMaps Journal"
excerpt: "The side panel of the StoryMaps Journal can be made visually even more appealing by adding dropdown buttons for a list of items."
date:   2018-03-21 09:12:00 +0100
categories: storymaps
image: "/images/storymaps/Capture006.PNG"
---



The steps to be followed are listed below:

1. The StoryMaps editor supports CSS styling in HTML. In the *source code* mode of the editor the `<style type=”text/css”> … </style>` tag with the desired CSS- styling can be added. For a clean appearance and to avoid conflicts, it should be added at the beginning of the section. <br>

<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture007.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>

2. Once the CSS `<style>` code has been added, it can be used anywhere in the section inside the HTML’s `<div class=”…”>` tag to create a dropdown menu. <br>

<span class="image center" style= "text-align:right;"><a class="image fit" target="_blank"><img src="/images/storymaps/Capture008.PNG" style= "width:100%; padding-bottom:0.5em;" alt="" /></a></span>

3. The items of the dropdown menu can also be made interactive by using the similar trick as explained in the [previous post](/storymaps/2018/03/21/Story-Actions-on-pictures.html).

The CSS styling used in the above example can be viewed at the [Story-Maps-Interface](https://github.com/ehasnain/Story-Maps-Interface) repository.

*Here is an example demonstrating the above trick:* [Supervised Theses at Esri Germany](http://esri-de-edu.maps.arcgis.com/apps/MapJournal/index.html?appid=2e8c944f3e424adcbf8e3db42a7e4114)