---
layout: splash
title: "Bare Metal User"
permalink: /docs/baremetal-user/
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/201106-CORP-BNR-Design-Centers-FPGAs-and-plds-Banner-2880x280.jpg
excerpt: "Welcome to the Bare Metal User page."
last_modified_at: 2018-01-10T11:22:01-05:00
---

# Introduction

Before attempting to run a bare metal application, please make sure that you are 
using the [latest release](https://github.com/polarfire-soc/icicle-kit-reference-design/releases) of the Icicle Kit Reference design. 
The process of programming the design using FlashPro Express programming tool 
is explained [here](https://github.com/polarfire-soc/polarfire-soc-documentation/blob/c4f74333d3b68efe0a6eb5ddfa1c95df6c020960/software-development/polarfire-soc-software-tool-flow.md#using-flashpro-express).

## Bare metal applications
To get started with the bare metal applications, a number of ready to use bare metal example applications are available at 
[polarfire-soc-bare-metal-examples](https://github.com/polarfire-soc/polarfire-soc-bare-metal-examples).

## The Platform software
Latest releases of the Microchip provided PolarFire SoC bare metal platform 
software are available at [platform](https://github.com/polarfire-soc/platform).

## SoftConsole
To use the bare metal applications, [download and install](https://www.microsemi.com/product-directory/design-tools/4879-softconsole#downloads)
the SoftConsole IDE. SoftConsole is Microchip's Eclipse based embedded software 
development IDE with support for RISC-V targets including PolarFire SoC. 
SoftConsole is available free of charge without a license.

## Hart Software Services (HSS)
The [HSS](https://github.com/polarfire-soc/hart-software-services) can act as a 
bootloader when you want your application to execute from RAM (DDR or LIM). 
Please refer to the [hss-payload-generator](https://github.com/polarfire-soc/polarfire-soc-documentation/blob/master/software-development/hss-payloads.md#role-of-the-hss-payload-generator-) for more information.

## References
To build your own applications and to understand more about the bare metal
project structure, refer to the [bare-metal-project-structure](https://github.com/polarfire-soc/polarfire-soc-documentation/bare-metal-project-structure).
