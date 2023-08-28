---
layout: post
title: "risc-v 5 stage pipelined processor"
category: computer-architecture
---

This project is a System Verilog implementation of a 5-stage pipelined RISC-V processor. The pipelining technique is a fundamental concept in modern processor design, enabling improved instruction throughput and performance by overlapping instruction execution stages.

## Project Overview

The pipelined processor implementation showcases the organization of a processor into five distinct stages: Fetch, Decode, Execute, Memory, and Writeback. Each stage is responsible for a specific part of the instruction execution process, allowing multiple instructions to be in different stages of execution simultaneously.

## Processor Architecture

The processor architecture follows the RISC-V instruction set, a popular open-source architecture designed for simplicity and modularity. The pipelining technique enables instruction-level parallelism, where instructions can progress through different stages simultaneously. This approach enhances the overall throughput of the processor.

## GitHub Repository

You can explore the source code and documentation for the pipelined processor on the GitHub repository [pipelined-processor](https://github.com/CgKaminski/toy-processors). Dive into the code to understand how pipelining improves performance and learn about the intricacies of organizing a processor into distinct stages.

---

**Note:** This pipelined processor implementation is designed to showcase the concept of pipelining and may not include all advanced features of a high-performance pipelined processor.
