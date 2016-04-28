---
layout: post
category: project
title: Arty Custom DDR3 controller
image: /images/blogs/2016-03-28-arty-ddr3.jpg
featured: false
tags:
- Artix
- DDR3 Controller
- Arty
---


Enjoy Digital, an FPGA design services company in France, have been playing with the (ARTY](http://www.xilinx.com/products/boards-and-kits/arty.html), a $99 Artix 7 FPGA kit. The board has 256 MB DDR3L, and Enjoy Digital have created an open-source custom DDR3 controller for the board which runs at 800Mbps/pin. 

{% include captionimage.html url="/images/blogs/2016-03-28-arty-ddr3.jpg" description="ARTY DDR3 opensource controller" %}

Find the full project on [GitHub: Arty SOC DDR3 Controller](https://github.com/enjoy-digital/arty-soc)

Testing also makes use of LiteEth, also from Enjoy Digital, and other opensource cores. LiteEth a small footprint and configurable open-source Ethernet core with UDP/IP hw stack and Etherbone frontend.

Check out the [Enjoy Digital Cores webpage](http://www.enjoy-digital.fr/cores.html) for more interesting open source projects including SATA, USB, and PCIe open-source cores. 

