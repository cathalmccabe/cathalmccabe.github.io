---
layout: page
title: About FPGAs
permalink: /fpgas/
---

### About FPGAs

Field Programmable Gate Arrays (FPGAs) are semiconductor devices that are based around a matrix of configurable logic blocks (CLBs) connected via programmable interconnects. FPGAs can be reprogrammed to desired application or functionality requirements after manufacturing. This feature distinguishes FPGAs from Application Specific Integrated Circuits (ASICs), which are custom manufactured for specific design tasks. Although one-time programmable (OTP) FPGAs are available, the dominant types are SRAM based which can be reprogrammed as the design evolves. - Learn More


### Getting Started
To design an FPGA you need to write some code. VHDL and Verilog are low level hardware description languages. You need FPGA design software to convert this code into a programming file for the FPGA. 
Compiling a design for an FPGA is more difficult than compiling software for a processor. You need to "Synthesize" the VHDL or Verilog code to convert it into a library of components the design software understands. The low-level components need to be mapped onto the FPGA device you are using, and the correct connections made between all the different components on the chip. THis is a very difficult problem for the tools to solve, as the designer can specify the clock speed of the device (and there may be many clock domains in the design which the tools need to take care of. Every path in the design must meet the timing specification. This process can taken a few minutes to a few hours or even days for a big and difficult design. 


### Get the software
The core Xilinx software is called Vivado. Download Vivado HLx edition for free, and install it. 
www.xilinx.com/download
You will have the option to generate a free license during the install. Xilinx mainly makes money from selling chips, and gives away most of their software for free. Only the very biggest, most expensive FPGAs are not supported in the free version. 

### Learn How to Program and FPGA
Learn about FPGAs
VHDL/Verilog
Vivado HLS
Vivado IP Integrator
SDSoC

### Get an FPGA board
There are a number of low cost boards available

Basys 3

Zybo

www.digilentinc.com

### Tutorials



### Your first FPGA project


### Your first Zynq project

### HLS

### Vivado IP Integrator

### Going further
Check out the training material

SDAccel