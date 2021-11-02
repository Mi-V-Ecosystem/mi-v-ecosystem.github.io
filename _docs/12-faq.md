---
layout: splash
title: "FAQ"
permalink: /docs/faq/
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/201106-CORP-BNR-Design-Centers-FPGAs-and-plds-Banner-2880x280.jpg
excerpt: "Welcome to the FAQ page."
last_modified_at: 2018-01-10T11:22:01-05:00
---

# FAQ 

Q1. How do I read the Libero Soc / SoftConsole versioning numbers 

A1: For Libero SoC  v (version) 2021(year). 2( release number of the year) 
   For SoftConsole v (version) 2021(year). 1 (release number of the year) 

Q1.1 Which versions of Libero SoC and SoftConsole should be used together.

A1.1: It is advised to use the latest Libero SoC and SoftConsole versions. 

Q2. What licence does Development kit X work with? 

A2.

| Development Kit | FPGA Part  | Supplied License | Minimum License | 
| -----------     | -----------| -----------      | -----------     |
| PolarFire Avalanche Kit  | MPF300TS-FCG484E     | Gold   | Silver |
| PolarFire Evaluation Kit | MPF300TS-1FCG1152I   | Gold   | Silver |
| PolarFire Splash Kit     | MPF300T-1FCG484E     | Gold   | Silver | 
| PolarFire Everest Kit    | MPF300TS-1FCG1152EES | Gold   | Silver |
| PolarFire SoC Icicle Kit | MPFS250T-FCVG484EES  | Silver | Silver |


Q3. Which version of Libero SoC and SoftConsole does the latest Icicle reference design use? 

A3: The Icicle Kit reference design states the minimum Libero SoC and SoftConsole version numbers. For more information it is advised to read the readme for the [reference design](https://github.com/polarfire-soc/icicle-kit-reference-design). 

Q4. Are there any tutorials available? 

A4: Yes, there are many tutorials on the Microchip YouTube channel. These can be accessed through the Training tab on the Mi-V Ecosystem page or through this [link](https://mi-v-ecosystem.github.io/docs/training/) 

Q5. how do I restore my development kit to a known good state? - Release of Kit design and Yocto  

A5: There is a training video which describes this process available [here](Getting Back to Factory Defaults) 

Q6. Do I need to use libero to develop software of PolarFire SoC :   

A6: No, download the reference bitstream and one of the build systems ( Yocto or Buildroot) 

Q7. How do I program a PolarFire SoC FPGA? 

A7: If a  FPExpress file is already generated then you can program the PolarFire SoC FPGA with the bitstream through FPExpress. Or if you are generating your own FPGA design you can use Libero SoC to download the bitstream to the PolarFire SoC FPGA. The [Getting Back to Factory Defaults](https://www.youtube.com/watch?v=dL3u6pYWFvQ&list=PL9B4edd-p2ajvXj0ZflizZI4zgm3Jev_O&index=5) demonstrates how to program the PolarFire SoC FPGA. 

8. 

Q8.1 What is Libero SoC? 

A8.1: Libero SoC is the development environment for Microchip FPGAs. It allows design, synthesis and bitstream generation as well as timing and power information.  

Q8.2 What is SoftConsole? 

A8.2: SoftConsole is the development environment for Bare-metal designs for the PolarFire SoC, Mi-V RV32 as well as Arm Cortex M3/1. SoftConsole is not intended for development of Linux.  

Q8.3 What is FPExpress? 

A8.3: FPExpress is a programming tool which enables programming of the Microchip FPGA with bitstreams. A programming job file is generated in Libero that can be programmed to the FPGA  

Q8.4 What is FlashPro5/6? 

A8.4: FlashPro5/6 are standalone programming devices that are used to download bitstreams to the Microchip FPGA. 

Q8.5 What is Embedded FlashPro6? 

A8.5: Embedded FlashPro6 or eFP6 is the on-board programmer available on the PolarFire SoC Icicle Kit. 

Q9. How much do tools for Icicle Kit cost? 

A9: The device which is on the Icicle Kit is supported with the Libero Silver licence. This allows users to use Libero SoC and SoftConsole free of charge.            

Q10. Do I need an Embedded FP6? 

A10:  Yes, it is a part of the Icicle Kit. A FlashPro6 is available for boards without an Embedded FP6. 
 
