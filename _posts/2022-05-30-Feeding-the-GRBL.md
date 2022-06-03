---
layout: post
title: "Feeding the GRBL"
description: "Configuring OpenBuilds CONTROL and GRBL"
tags: MilkCr8 CNC
---
## Feeding the GRBL

Remember, the whole point of this journey is to be able to get a machine to do what you want it to do.  That's the whole Computer-Numerical-Control thing, commonly abbreviated CNC.  What many of us forget is that we are NOT building a machine that'll do what we WANT it to do -- instead, we're build a machine that'll do what we TELL it to do.  When we start to snap endmills like last week's pretzel, it is becuase we really DID tell the machine to dive sideways at rapid speed, instead of gently dipping our proverbial endmill toes into the water (aluminum).  

All our hopes and dreams are converted to GCODE.  There are many different ways to get GCODE from your CAM software to your machine.  Our MilkCr8 designer Joe suggested the OpenBuilds BlackBox controller, and while no one would mistake the BlackBox for the "latest hotness" here in 2022, it is an excellent choice for a project just as the MilkCr8.  It is well documented, proven, and comes with really decent software to control the machine called OpenBuilds CONTROL.  



[Link to OB CONTROL]([https://github.com/JohnOCFII/johnocfii.github.io/blob/main/assets/images/IMG_1092.jpeg](https://software.openbuilds.com)


![MilkCr8 CNC software](/assets/images/OpenBuildsCONTROL.png)

The Openbuilds documentation is really quite good.  They've also got some good YouTube videos (look at their Lead 1010 videos) that walk you through the software configuration and initial movement tests.  Fellow MilkCr8 builder Adam provided me his GRBL config, but initially, you'll want to turn off the soft limits and manually home and figure out your own max X, Y, and Z distances before you re-enable soft limits.



## This blog entry still under constuction
