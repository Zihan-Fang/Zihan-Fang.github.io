---
title: "FPGA Project in CS@Fudan"
excerpt: "A PCIe data acquisition board is designed to verify the hardware and algorithm of 8 ADC time interleaved sampling based on Virtex-7 FPGA.<br/><br/><img src='/images/FPGA_project.png' alt='FPGA_project' width='1920' height='1280' style='max-width: 400px'>"
type: "January 2022 - June 2023"
venue: "Supervisor: Prof. Yue Gao, Department of Computer Science, Fudan University"
date: 2023-06-30
collection: experience
---

# <img src="/images/FPGA_project.png" alt="FPGA_project" width="1600" height="1200" style="max-width: 400px" class="left" data-proofer-ignore>
  
  - A PCIe data acquisition board is designed to verify the hardware and algorithm of 8 ADC time interleaved sampling based on Virtex-7 FPGA.
  - 8 ADCs with a sampling rate greater than 50MSPS and a quantization accuracy of 14bits is adopted. 
  - The delay of the sampling time in ADC is controlled by clock registers to realize interleaved sampling.  
  - The sampling data is transmitted to FPGA internal calibration algorithm with JESD204B protocol and is transferred to the hard disk for storage through the PCIE interface.
  - SPI configuration, BRAM control and cross clock domains processing are also involved.
  - A upper computer software is realized to perform subsequent data processing and graph display.
