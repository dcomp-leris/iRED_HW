# Purpose of this repository
This repository aims to make the artifacts used in article "iRED: A disaggregated P4-AQM fully implemented in programmable data plane hardware (Transactions on Networking - Submitted)" available.

# Definition
ingress Random Early Detection (iRED) as a more efficient P4-AQM approach fully implemented in PDP hardware, that introduces the concept of disaggregated AQM, effectively resolving the egress drop problem. iRED also supports the Low Latency, Low Loss, and Scalable Throughput (L4S) framework, saving device pipeline resources by dropping packets in the Ingress block. Our experiments with a Tofino2 programmable switch achieved a rate of 1Tbps and show that iRED can reduce router resource consumption by up to 10x in memory usage, 12x fewer processing cycles, and 8x less power consumption for the same traffic load. 

# Design of iRED
![alt-text](https://github.com/dcomp-leris/DESiRED/blob/main/figs/iRED.jpg)

# Folders
```console
.
├── figs # figures
├── README.md
└── src # iRED source code 
```