---
title: "FPGA Project"
collection: experiences
permalink: /experience/2023_FPGA_Project
excerpt: "January 2022 - June 2023 <br/><img src='/images/FPGA_project.png'>"
date: 2023-06-30
venue: "Supervisor: Prof. Yue Gao, Department of Computer Science, Fudan University"
locate: "Department of Computer Science, Fudan University"
---


# alt="FPGA_project" width="1000" height="800" style="max-width: 400px" class="left" data-proofer-ignore>
  
  - A PCIe data acquisition board is designed to verify the hardware and algorithm of 8 ADC time interleaved sampling based on Virtex-7 FPGA.
  - 8 ADCs with a sampling rate greater than 50MSPS and a quantization accuracy of 14bits is adopted. 
  - The delay of the sampling time in ADC is controlled by clock registers to realize interleaved sampling.  
  - The sampling data is transmitted to FPGA internal calibration algorithm with JESD204B protocol and is transferred to the hard disk for storage through the PCIE interface.
  - SPI configuration, BRAM control and cross clock domains processing are also involved.
  - A upper computer software is realized to perform subsequent data processing and graph display.
