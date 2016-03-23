---
layout: post
category: blog
title: Xilinx Zynq powering BBC radio data encoding
image: /images/blogs/2016-02-11-bbc_zedboard.jpg
featured: true
tags: 
- BBC
- Zynq
- Zedboard
- Audio Processing
- Featured
---

Zynq at the BBC!
The BBC is the world's oldest and largest national broadcaster providing extensive radio, TV, and online services in the UK and Worldwide. 

While the BBC is well-know around the world for broadcasting, it is less well know that the BBC have a strong research and development arm,  established by royal charter. BBC R&D

The BBC national radio services are transmitted around the UK using an audio coding system called NICAM 3. NICAM stands for Near Instantaneous Companded Audio Multiplex and is an early form of lossy compression for digital audio. It was originally developed in the early 1970s for point-to-point links within broadcasting networks.

Justin Mitchell, principal engineer at BBC R&D recently shared a story about a NICAM upgrade project at the BBC that made use of a Xilinx Zynq device. The first NICAM digital stereo programme was broadcast in 1986. The NICAM equipment originally installed around this time was failing with age, and with supply of spare parts an issue, a major upgrade became necessary. 

At the heart of the new system is a Xilinx Zynq chip carrying out data combining and splitting, 6-channel NICAM3 audio encoding and decoding, CRC insertion and checking. Zynq combines Xilinx FPGA fabric, ideal for data processing, with an ARM dual core A9 allowing higher level analytics to be run, along with a full operating system to provide high level user services and interfaces.

![BBC Zedboard]({{ site.baseurl }}/images/blogs/2016-02-11-bbc_zedboard.jpg) 

According to Justin Mitchell, principal engineer at BBC R&D "the output of these coders are listened to by about 61% of the UK population (35-40 million people) each week. When millions of people woke up and listened to the BBC national radio services, nobody noticed that anything had changed. For a technology change project this is an excellent result."

See here for the original story:

http://www.bbc.co.uk/rd/blog/2016-01-35-million-people-didnt-notice-a-thing-dot-dot-dot





