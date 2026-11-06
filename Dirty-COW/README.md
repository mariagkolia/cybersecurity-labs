
# Dirty COW Attack Lab

## Overview
Academic cybersecurity lab focused on exploring the Dirty COW (CVE-2016-5195) Linux kernel vulnerability, race conditions, and privilege escalation in a controlled virtual environment.

## Lab Exercises
- Investigating the Dirty COW vulnerability
- Modifying a read-only file through vulnerability exploitation
- Exploring Linux file permissions and memory mapping
- Demonstrating privilege escalation in a vulnerable Linux environment
- Understanding the role of Copy-on-Write (COW) mechanisms

## Tools & Technologies
- Linux
- C Programming (lab code execution and modifications)
- GCC
- Linux File Permissions
- Memory Mapping (mmap)
- Multithreading

## Learning Outcomes
- Explored how the Dirty COW vulnerability affects Linux memory management.
- Investigated race conditions in the Copy-on-Write mechanism.
- Demonstrated the modification of a read-only file in a vulnerable environment.
- Examined how a vulnerability can lead to privilege escalation.
- Gained practical understanding of Linux user privileges and access controls.

## Results
The initial experiment successfully demonstrated the modification of a read-only file through the Dirty COW vulnerability.

The second experiment demonstrated privilege escalation by modifying a user account's UID in the vulnerable lab environment.

## Lab Report
[View the full lab report](./Dirty-Cow-lab.pdf)

## Disclaimer
All experiments were conducted in a controlled academic environment for educational purposes.
