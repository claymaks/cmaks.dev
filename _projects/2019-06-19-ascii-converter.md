---
layout: project
title: ASCII Image Converter
description: Takes image as input and outputs a .txt of the image.
summary: Takes image as input and outputs a .txt of the image.
category: ascii, python, cv2, image, team
---

<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>


Over the summer, I worked on several small projects with a 
<a href="https://schemberizer.github.io/Personal-Website/" target="_blank">close friend of mine, Josh.</a>
This script takes an image as input and outputs text files filled with characters having different
pixel densities to recreate the image.  After our initial pass programming this script,
we spent time optimizing, being able to process an 8.5mb file in under ten minutes
(that's 4032x3024 pixels).  Clicking these images redirects to text documents, but you can
also see some more <a href="https://github.com/claymaks/ascii_converter" target="_blank">
on my github.</a>

<div class = "row">
    <div class = "column">
        <a href="/assets/img/pro/ascii/shoes84x87-0.txt" target="_blank">
        <img src="/assets/img/pro/ascii/shoes.png" height="250px" alt="1"/>
        </a>
    </div>
    <div class = "column">  
        <a href="/assets/img/pro/ascii/josh812x1584-0.txt" target="_blank">
        <img src="/assets/img/pro/ascii/josh.png" height="250px" alt="2"/>
        </a>
    </div>
</div>

