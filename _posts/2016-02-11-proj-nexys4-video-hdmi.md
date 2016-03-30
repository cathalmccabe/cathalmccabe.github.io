---
layout: post
category: project
title: Video processing on the Digilent Nexys Video
image: /images/blogs/n4_video_hdmi.jpg
featured: true
tags:
- Artix
- Video Processing
- Nexys Video
---


This project from Mike Filed of (Hamsterworks)[http://hamsterworks.co.nz] shows how to take 1080p HDMI in do some processing, and send it to the HDMI out on the Digilent Nexys Video board which uses the Xilinx Artix 200T.

In this case, edge detection and a grid overlay can be switched on or off using the dip-switches on the board. The design also detects and displays the audio levels.

A YouTube video showing the edge detection in action can be viewed here:

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=hHVcPGt3IiU" frameborder="0" allowfullscreen></iframe>


You can read the full project description on the project webpage:

(Hamsterworks HDMI video processing)[http://hamsterworks.co.nz/mediawiki/index.php/HDMI_Processing]

Full source code for the project is available on the project GitHub page:

(Hamsterworks GitHub Artix 7 HDMI Image processing)[https://github.com/hamsternz/Artix-7-HDMI-processing]