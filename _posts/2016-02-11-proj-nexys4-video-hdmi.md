---
layout: post
category: blog
title: Video processing on the Digilent Nexys Video
image: /images/blogs/n4_video_hdmi.jpg
tags:
- Artix
- Video Processing
- Nexys Video
---


This project from Mike Filed of http://hamsterworks.co.nz shows how to take 1080p HDMI in do some processing, and send it to the HDMI out on the Digilent Nexys Video board which uses the Xilinx Artix 200T.

In this case, edge detection and a grid overlay can be switched on or off using the dip-switches on the board. The design also detects and displays the audio levels.

A YouTube video showing the edge detection in action can be viewed here:
https://www.youtube.com/watch?v=hHVcPGt3IiU

You can read the full project description on the project webpage:

http://hamsterworks.co.nz/mediawiki/index.php/HDMI_Processing

Full source code for the project is available on the project GitHub page:

https://github.com/hamsternz/Artix-7-HDMI-processing