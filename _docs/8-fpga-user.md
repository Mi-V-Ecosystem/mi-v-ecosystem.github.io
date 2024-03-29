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

1. Import the Icicle Kit [reference design](https://github.com/polarfire-soc/icicle-kit-reference-design/releases) into Libero SoC Design Suite.
2. If you wish to change the MSS Fabric Interface:
   - Launch the MSS Configurator.
   - Add/edit the peripherals.
   - Change the pin assignment of the MSS peripherals.
   - Configure the FIC.
   - Configure the clocks.
   - Change the MSSIO configuration.
   - Configure DDR/L2 memory partition.
   - Generate the MSS configuration as a MSS component file (cxz).
3. Follow the Libero SoC design flow:
   - Import the MSS component.
   - Add custom HDL.
   - Add timing constaints.
   - Synthesize.
   - Place and Route.
   - Initialize eNVM client with HSS binary built with the configuration created in step 2.
4. If you wish to decode the FIC address in the fabric, export the Libero memory map and hand over this information to the software developer to import into the embedded flow.   
6. Program and test the bitstream.


### Reference Material
[UG0758 User Guide PolarFire FPGA Design Flow Libero SoC](http://coredocs.s3.amazonaws.com/Libero/12_5_0/Tool/pf_des_flow_ug.pdf)

[MSS configurator tool](https://onlinedocs.microchip.com/pr/GUID-BC096324-C726-48DB-8987-EF2BBC748A73-en-US-1/index.html)

