---
layout: project
title: Fisher AGV
description: Autonomously Guided Vehicle made at Fisher Dynamics.
summary: Autonomously Guided Vehicle made at Fisher Dynamics.
category: python, c++, c#, flask, hero, raspberry pi, lidar, private
---

From May 2019 to January 2021, I led the development of custom autonomously guided vehicles at Fisher Dynamics.  After seeing demonstrations of various AGVs, I was fixated on the high cost. Throughout my time at Fisher, I implemented "local GPS" using digital signal processing, LIDAR and RFID scanners for navigation and state control, and a centralized server that could handle the hundred requests our devices threw at it every second.  

While I learned a lot during this project, it's very easy for me to look at all the changes I would like to make now.  Regardless, I would love to talk to you about the mistakes I made and how I learned from them.

Below are videos from around March through December 2020.  This excludes much of the early development of the system.  **While I have permission to share this media with you, I ask that you do not distribute it.**


<style>
html, body {
    height:100%;
    width:100%;
    margin:0;
}
</style>

<iframe width="560" height="315" src="https://www.youtube.com/embed/xXdy7Id8FnA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Timelapse - Stations
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/uACyR2hHOEU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Timelapse - Forklift
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/w403Gb-o7oo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
State-based collision avoidance tests.  At this time, we were using Banner safety scanners to handle emergency stops, but we have since moved to RPLidars.  In this scenario, the scanner is never triggered, and all collision avoidance is handled through the server.
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/pV6JuL4rxOM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Robot passing under tote
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/2_ivGJrXmxk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Pin demonstration upon leaving station
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/cknJdaglXFo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Demonstration monitoring software, with video included.
<br><br><br><br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/WPVmF5ucIvY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
Testing forklift / robot interaction.  After forklift completes task, operator holds down button, signaling to the robot that it is good to go.