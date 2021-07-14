---
layout: splash
title: "FPGA User"
permalink: /docs/fpga-user/
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/201106-CORP-BNR-Design-Centers-FPGAs-and-plds-Banner-2880x280.jpg
excerpt: "Welcome to the FPGA User page."
---

### FPGA Developer 

1. Import the Icicle Kit Libero SoC [reference design](https://github.com/polarfire-soc/icicle-kit-reference-design/releases)
2. If you wish to change the MSS Fabric Interface:
   - Launch the MSS Configurator.
   - Add/edit the peripherals.
   - Change the pin assignment of the MSS peripherals.
   - Configure the FIC.
   - Configure the clocks.
   - Change the MSSIO configuration.
   - Configure DDR/L2 memory partition.
   - Generate the MSS configuration.
3. Follow the Libero SoC design flow:
   - Import the MSS component.
   - Add custom HDL.
   - Add timing constaints.
   - Synthesize.
   - Place and Route.
   - Initialize eNVM client with HSS binary built with the configuration created in step 2.
4. Are you further decoding the FIC address in the fabric?
5. If yes, export the Libero memory map, if not continue to point 6.
   - Hand over this information to the software developer. 
7. Program and test the bitstream.
