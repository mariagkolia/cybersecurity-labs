
# Race Condition Vulnerability Lab

## Overview
Academic cybersecurity lab focused on exploring Time-of-Check to Time-of-Use (TOCTOU) race condition vulnerabilities, Linux privilege escalation, and security countermeasures in a controlled virtual environment.

## Lab Exercises
- Examining Set-UID programs and Linux file permissions
- Understanding TOCTOU vulnerabilities
- Testing a race condition attack involving symbolic links
- Exploring an improved attack method using atomic symbolic link exchange
- Applying the Principle of Least Privilege
- Testing Ubuntu's built-in symbolic link protections

## Tools & Technologies
- Linux (Ubuntu)
- C Programming
- GCC
- Bash Scripting
- Set-UID Programs
- Symbolic Links

## Learning Outcomes
- Investigated how TOCTOU vulnerabilities arise between file permission checks and file access.
- Explored how race conditions may lead to privilege escalation.
- Compared different approaches to exploiting race condition vulnerabilities.
- Applied and evaluated security countermeasures in Linux.
- Gained a better understanding of the Principle of Least Privilege.

## Results
The initial race condition attack attempt was unsuccessful.

An improved method using atomic symbolic link exchange successfully demonstrated the vulnerability in the lab environment.

Applying the Principle of Least Privilege and enabling Ubuntu's built-in symbolic link protection prevented the attack in subsequent experiments.

## Lab Report
[View the full lab report](./Race-Condition-vulnerabilities-lab.pdf)

## Disclaimer
All experiments were performed in an isolated academic environment for educational purposes.
