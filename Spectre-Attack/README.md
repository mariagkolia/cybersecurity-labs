
# Spectre Attack Lab

## Overview
Academic cybersecurity lab focused on exploring the Spectre vulnerability, speculative execution, branch prediction, and CPU cache side-channel attacks in a controlled virtual environment.

## Lab Exercises
- Measuring CPU cache versus main memory access times
- Exploring FLUSH+RELOAD as a cache side-channel technique
- Investigating out-of-order execution and branch prediction
- Running a basic Spectre attack experiment
- Testing modifications intended to improve attack accuracy

## Tools & Technologies
- Linux
- C Programming (lab code execution and modifications)
- GCC
- CPU Cache Analysis
- Virtual Machine Environment

## Learning Outcomes
- Analyzed cache hits and cache misses through memory access timing.
- Explored how speculative execution can leave observable traces in CPU cache.
- Investigated the relationship between branch prediction and information leakage.
- Evaluated the reliability and limitations of Spectre attack experiments.

## Results
The FLUSH+RELOAD experiment successfully identified the expected secret value.

The basic Spectre experiment recovered the first byte of the secret in one execution, although false positives were observed.

The modified version did not consistently recover the expected value, highlighting the influence of cache noise and execution environment on attack reliability.

## Lab Report
[View the full lab report](./Spectre-Attack-lab.pdf)

## Disclaimer
All experiments were conducted in a controlled academic environment for educational purposes.
