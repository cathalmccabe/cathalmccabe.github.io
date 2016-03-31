---
layout: page
title: About FPGAs
permalink: /fpgas/
---

### New to FPGAs? 
FPGAs offer a number of advantages over other types of semi-conductor devices, but are less well known outside the FPGA community. Getting started with FPGAs can be a challenge, so this page aims to provide a gentle introduction to the world of FPGAs

### About FPGAs

Field Programmable Gate Arrays (FPGAs) are semiconductor devices (chips) that consist of large arrays of logic cells. A single logic cell can be used to implement logic and mathematicaly functions. E.g. AND, OR, NOT, multiply etc. FPGAs contain many of these cells which can be connected together to form more complex logic functions. FPGA competitors are CPUs, GPUs, and ASICs. 

FPGAs typically run at a slower clock speed (hundreds of MHz) than for example CPUs (GHz) and GPUs (MHz - GHz), but are massively parallel. 
For example, a modern processor running at say 2GHz, that can carry out 1 multiply per clock cycle can carry out 2 billion multiplications per second.

An FPGA, running at say 200 MHz, with 2,000 multipliers (1 multiply per clock cycle)  can carry out 400 billion multiplications per second. The largest Xilinx Virtex Ultrascale FPGAs today have over 10,000 multipliers.

FPGAs can be reprogrammed or reconfigured, which means the same FPGA can be used for many different applications. This feature distinguishes FPGAs from Application Specific Integrated Circuits (ASICs), which are custom manufactured for specific design tasks.


### Getting Started
To design an FPGA you need to write some code. VHDL and Verilog are low level hardware description languages that have been used for many years to program FPGAs. You need FPGA design software to convert this code into a programming file for the FPGA. 

Compiling a design for an FPGA is more difficult than compiling software for a processor. You need to "Synthesize" the VHDL or Verilog code to convert it into a library of components that can be mapped onto the FPGA logic cells. This is a very difficult problem for the tools to solve, as the designer can specify the clock speed of the device, and there may be multiple clock domains in the design. Every path in the design must meet the timing specification. This process can taken a few minutes to a few hours for the biggest designs. 

### Get the software
The core Xilinx software is called Vivado. Download Vivado HLx edition for free:
(www.xilinx.com/download)[www.xilinx.com/download]

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