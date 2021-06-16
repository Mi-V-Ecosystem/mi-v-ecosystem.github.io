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
  2a. If yes, open the MSS configurator.
  2b. Add/edit the peripherals.
  2c. Changethe pon assignment of the MSS peripherals.
  2d. Edit the FIC configuration.
  2e. Edit the clock configuration.
  2f. Change the MSSIO congiguration.
  2g. Edit the L2 memory partition.
  2h. continue onto point 3.
3. if not,  import the MSS component.
3a. Add custom HDL.
3b. Synthesize.
3c. Place and Route.
3d. Initialize eNVM client with HSS binary.
3e. Program hardware.
4. Are you further decoding the FIC address in the fabirc?
5. if yes, export the libero memory map, if not continue to point 6.
6. Program and test the bitstream.


### Libero SoC 
[Libero Download page](https://www.microsemi.com/product-directory/design-resources/1750-libero-soc#downloads)

#### Libero Licenses 
[Libero License page](https://www.microsemi.com/product-directory/design-resources/1711-licensing#overview)

[Free Libero Silver License](https://soc.microsemi.com/portal/default.aspx?r=1)

[Paid Libero Licenses](https://soc.microsemi.com/portal/default.aspx?r=1)

### SoftConsole

[SoftConsole](https://www.microsemi.com/product-directory/design-tools/4879-softconsole#downloads)
