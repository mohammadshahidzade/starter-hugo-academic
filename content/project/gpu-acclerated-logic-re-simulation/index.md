---
title: GPU Acclerated Logic re-simulation
date: 2021-11-03T19:30:21.354Z
summary: I designed and implemented a new method to optimally parallelize the
  verilog design of various circuits. I used C++, CUDA and verilog.
draft: false
featured: false
tags:
  - Cpp
links:
  - icon_pack: fas
    url: http://iccad-contest.org/2020/index.html
    name: CAD Contest
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Timing-aware gate-level simulation usually runs much slower than RTL simulation, from a few cycles per second on smaller unit-level designs to many seconds per cycle on today’s largest full-chip SoC designs. In this project, I developed several methods to parallelize the computations in the two dimensions of gate-parallelism and stimuli-parallelism and a new method for memory management of the stored signal waveforms. I did most of the project using C++ and the CUDA library and used several parallelization techniques. In addition, I developed a parser for Verilog as well as a Verilog-to-C++ translator. Our project managed to speed up the simulation up to 40x compared to a CPU simulator.