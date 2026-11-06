
# Meltdown Attack Lab

## Overview
Academic cybersecurity lab focused on exploring the Meltdown vulnerability, CPU cache side-channel techniques, and kernel memory protection in a controlled virtual environment.

## Lab Exercises
- Measuring CPU cache versus main memory access times
- Exploring FLUSH+RELOAD as a cache side-channel technique
- Understanding kernel and user-space memory isolation
- Handling memory access violations in C
- Investigating out-of-order execution
- Experimenting with Meltdown attack techniques

## Tools & Technologies
- Linux
- C Programming
- GCC
- Linux Kernel Modules
- CPU Cache Analysis

## Learning Outcomes
- Analyzed differences between cache hits and cache misses.
- Explored how cache timing can reveal information.
- Investigated memory access restrictions and CPU execution behavior.
- Tested Meltdown attack variations and analyzed their limitations.

## Results
The FLUSH+RELOAD experiment successfully identified the expected secret value.

However, the Meltdown attack experiments did not recover the expected secret from kernel memory in the tested environment. Hardware and software mitigations may have influenced the results.

## Lab Report
[View the full lab report](./Meltdown-Attack-lab.pdf)

## Disclaimer
All experiments were conducted in a controlled academic environment for educational purposes.
