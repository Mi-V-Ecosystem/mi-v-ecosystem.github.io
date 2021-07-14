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

1. Import the Icicle kit libero [reference design]()
2. Are you changing the MSS Fabric Interface?
  a. If yes, open the MSS configurator.
  b. Add/edit the peripherals.
  c. Change the pin assignment of the MSS peripherals.
  d. Edit the FIC configuration.
  e. Edit the clock configuration.
  f. Change the MSSIO congiguration.
  g. Edit the L2 memory partition.
  h. continue onto point 3.
3. if not,  import the MSS component.
  a. Add custom HDL.
  b. Synthesize.
  c. Place and Route.
  d. Initialize eNVM client with HSS binary.
  e. Program hardware.
4. Are you further decoding the FIC address in the fabirc?
5. if yes, export the libero memory map, if not continue to point 6.
6. Program and test the bitstream.

