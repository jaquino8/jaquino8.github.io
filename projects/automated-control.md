---
layout: project
type: project
image: images/labview.jpg
title: Automated Control Group
permalink: projects/automated-control
# All dates must be YYYY-MM-DD format!
date: 2020-09-04
labels:
  - LabVIEW
  - Image Processing
summary: Striving to implement an automated control feature to the Red Tweezers program ran through LabVIEW
---

For my x96 and Capstone project courses I helped develop automated movement functions to be implemented in a Red Tweezers program. This program is ran via LabVIEW and uses NI Vision Acquisition. It uses video input to detect microscopic objects then generate and control the movement of microscopic actuators. My group is responsible for developing the movement algorithms that will be responsible for caging the detected object and moving it.

The program has two components that need to be modified in order to achieve the automated control. The first is the front panel shown here:
<img class="ui large left rounded image" src="/images/acs-front-panel.png">

This front panel provides the graphical user interface to watch real time. The [original Red Tweezers program](https://www.gla.ac.uk/media/Media_301250_smxx.pdf) was modified to include movement functions that would allow the user to select locations for the micro actuators, or microrobots, to move to. By using multiple microrobots, we could then attempt to "cage" an object and move it to another location.

I was placed on a team that was developing a movement function to allow a microrobot to move in an arc motion. A snippet of the code is show here:
<img class="ui large left rounded image" src="/images/arc-code.png">

This code is placed in the block diagram section of LabVIEW. It took a while to understand the syntax and method to code using this type of software. As shown in the photo above, LabVIEW uses a graphical coding approach unlike the text based languages such as C++ or Java. The code above uses the microrobot location and user selected endpoint to generate points of the microrobots movement. This code implements trigonometery calculations to generate the X and Y coordinates to be stored into an array shown in other sections of the code.

This program is still under development.
