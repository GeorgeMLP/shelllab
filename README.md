# Shell Lab

## Introduction

ICS Shell Lab, Peking University.

The purpose of this assignment is to get more familiar with the concepts of process control and signalling. You’ll do this by writing a simple Linux shell program that supports a simple form of job control and I/O redirection. For more information about this lab, please refer to ```tshlab.pdf```.

## Installation

It is recommended to do this lab on Ubuntu 22.04. Make sure you have glibc version >= 2.34. You can check the glibc version with this command:
```
ldd --version
```

Ubuntu 20.04 or older does not support glibc 2.34, so you need to update it before doing this lab.

## Score

There are 32 trace files at 4 points each that you need to pass. My implementation in ```tsh.c``` passes all trace files.
