---
layout: post
title: "hack processor"
category: hardware
---

This project is a System Verilog implementation of the Hack-Processor, a 16-bit computer processor introduced in the NAND to Tetris course. The NAND to Tetris course, also known as "From Nand to Tetris: Building a Modern Computer from First Principles," is an educational program offered by the Hebrew University of Jerusalem. More information can be found on their [official site](https://www.nand2tetris.org/).

## The Nand to Tetris Course 

The aforementioned “Nand to Tetris” course, is an educational program that I took in the past that leads you through building a 16-bit computer using Nand gates. The program is a fantastic introduction to computer architecture; however, it leads you to build components using their own HDL language. For simplicity, their HDL-1 and hardware simulators are great, however they’re limited in usability. Thus, after I completed the course traditionally, I chose to redo the course using the industry standard [systemVerilog HDL](https://en.wikipedia.org/wiki/SystemVerilog) and [Verilator simulator](https://www.veripool.org/verilator/).

## Processor Architecture  

The Hack-Processor features a Harvard architectural design with separated instruction and data memory, allowing for simultaneous instruction fetch and data access. Much of the processor’s architecture has been simplified for educational purposes, as such there is no pipelining and an absence of hardware implementation for multiplication and division. Furthermore, the goal of this project was to create an as accurate implementation as possible of the Hack CPU, thus I was uninterested in computational optimizations.

The below is a logic level representation of the hack-processor as explicitly defined in my HDL-1 implementation.  

![hack processor architecture](/assets/img/hack-processor.png)

## GitHub Repository

My solution to both the systemVerilog and hdl-1 implementation can be found on my GitHub repo [hack-processor](https://github.com/CgKaminski/hack-processor/tree/main). Additionally, I have some further documentation on how to use the processor simulator if desired.

