---
layout: post
title: Ball Machine Screw Conveyor
description:  I modeled a miniature screw conveyor in SolidWorks for a 10 mm ball machine. I made custom parts that were 3D printed on a Creality Ender 3 Pro and sliced on Ultimaker Cura. I assembled the parts and made design modifications along the way for it to be functional in the end.
skills: 
  - CAD Modeling
  - SolidWorks
  - DFM/DFA
  - Rapid Prototyping 
  - FDM 3D Printing
  - Testing
  - Problem Solving

main-image: /images/IMG_20260412_205049412_30percent.jpg
---

---
# Design Problem 
I wanted to create a machine with moving elements and custom designed parts to practice CAD modeling as well as 3D printing. The assembly would also be a challenge in adjusting for tolerances between what is represented in the CAD model versus what is actually produced by the 3D printer.

# 3D Printer
I used a Creality Ender 3 Pro that I built and upgraded with a BTT SKR Mini E3 V3.0 motherboard and a BLTouch sensor for bed level compensation. Calibration was a challenge for awhile, but I have it dialed to a high degree. Ensuring proper X and Y belt tension (not too much and not too little) and bed level height (Z-offset) have helped improve quality. What has really helped with the bed leveling issues was replacing the stock bed springs and print bed with silicone spacers and PEI print bed. The silicone is much stiffer and more stable but still has some give if the print head presses into the bed. The PEI print bed is a great surface that makes it easier to clean and remove finished parts compared to the stock bed. These are 2 very inexpensive upgrades (silicone spacers were $8 and the PEI bed was $13), but it makes the print process much less frustrating.

# CAD Model

{% include image-gallery.html images="/images/Screenshot 2026-04-17 043540.png" height="600" %}
{% include image-gallery.html images="/images/Screenshot 2026-04-17 072456.png, /images/Screenshot 2026-04-17 074106.png" height="300" %}



# 3D Printing

{% include image-gallery.html images="/images/Screenshot 2026-04-17 074343.png" height="600" %}
{% include image-gallery.html images="/images/IMG_20260409_214928966_30percent.jpg, /images/IMG_20260410_113012547_30percent.jpg" height="100" %}

{% include image-gallery.html images="IMG_20260412_083254030_HDR_30percent.jpg" %}
{% include image-gallery.html images="IMG_20260412_175056965_HDR_30percent.jpg" %}
{% include image-gallery.html images="IMG_20260412_202720621_HDR_30percent.jpg" %}
{% include image-gallery.html images="IMG_20260412_205049412_30percent.jpg" %}
{% include image-gallery.html images="IMG_20260414_130711922_30percent.jpg" %}
{% include image-gallery.html images="IMG_20260416_113210308_HDR_30percent.jpg" %}

{% include youtube-video.html id="y1eAPTMESTk" autoplay= "false"%}
{% include youtube-video.html id="On4fK84VsZQ" autoplay= "false"%}
{% include youtube-video.html id="Y_Ba7DdIp_M" autoplay= "false"%}
{% include youtube-video.html id="jo282rZWr0A" autoplay= "false"%}

<br>
# Full Assembly


{% include image-gallery.html images="/images/IMG_20260417_091106043_30percent.jpg" %}

{% include image-gallery.html images="/images/IMG_20260417_100325737_30percent.jpg" %}

{% include image-gallery.html images="/images/IMG_20260417_091202726_HDR_30percent.jpg, /images/IMG_20260417_181133052_30percent.jpg, /images/IMG_20260417_181143822_30percent.jpg, /images/IMG_20260417_181630820_30percent.jpg" height="300" %}

<br>
{% include youtube-video.html id="6mobO4Vh4Ao" autoplay= "false"%}
{% include youtube-video.html id="fLjb5T3nCEM" autoplay= "false"%}


<br>
# Future Design Improvements
-I need to 3D print a spacer at the front of the trough. I noticed balls get caught between the front wall of the trough and the initial screw blade. Alternatively, I could adjust the CAD model to have the trough shorter to close the gap, but that would require reprinting it.

{% include image-gallery.html images="/images/Screenshot 2026-04-17 071555.png" height="400" %}

<br>-The output side of the trough CAD model needs the opening 2mm wider to lessen the probablity of balls getting stuck at the end of the travel. When I was doing the test run, I used cutters and pliers to manually snip and bend the flange of the opening to be wider.
<br>-I should shorten the front of the shaft at least 20 mm, so that the hub is not as close to the floor in the incline position.
<br>-I would like to add a small motor to eliminate the need to manually hand crank it.
<br>-The attachment of the motor may need a bevel gear to either fit it onto the front of the trough. Alternatively, the bevel gear would need its own gearbox and coupled to the input shaft of the screw conveyor.
<br>-I would like to add a hopper with a return feed and a gate check (using a micro switch or proximity sensor) programmed to an Arduino to regulate flow into the screw conveyor to prevent jams.
<br>


