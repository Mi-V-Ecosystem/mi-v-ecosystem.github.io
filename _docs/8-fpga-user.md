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

1. Import the Icicle kit libero [reference design](https://github.com/polarfire-soc/icicle-kit-reference-design/releases)
2. Are you changing the MSS Fabric Interface?
   - If yes, open the MSS configurator.
   - Add/edit the peripherals.
   - Change the pin assignment of the MSS peripherals.
   - Edit the FIC configuration.
   - Edit the clock configuration.
   - Change the MSSIO congiguration.
   - Edit the L2 memory partition.
   - continue onto point 3.
3. if not,  import the MSS component.
   - Add custom HDL.
   - Synthesize.
   - Place and Route.
   - Initialize eNVM client with HSS binary.
   - Program hardware.
4. Are you further decoding the FIC address in the fabirc?
5. if yes, export the libero memory map, if not continue to point 6.
6. Program and test the bitstream.
