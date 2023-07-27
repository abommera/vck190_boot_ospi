<tr>
   <td align="center"><img src="https://github.com/Xilinx/Image-Collateral/blob/main/xilinx-logo.png?raw=true" width="30%"/><h1>2021.1 Versal OSPI Boot Tutorial </h1>
   </td>
 </tr>
</table>

# Table of Contents

1. [Introduction](#introduction)

2. [Before You Begin](#before-you-begin)

3. [Building Hardware Design](#building-hardware-design)

4. [Building Software Design](#building-software-design)

5. [Running the Design](#running-the-design)

# Introduction
Versal™ ACAP combines adaptable processing and acceleration engines with programmable logic and configurable connectivity to enable custom, heterogeneous hardware solutions for a wide variety of applications in Data Center, automotive, 5G wireless, wired network, and defense. Versal ACAP supports several primary boot modes for application flexibility. This tutorial highlights the OSPI primary boot mode flow in sinlge mode.

The octal SPI (OSPI) boot mode has an SPI compatible serial bus interface with extended octal commands. Standard Serial Peripheral Interface (SPI) is supported along with high performance Octal SPI variants. The OSPI boot mode supports an 8-bit data bus width and single transfer rate (STR) during the RCU BootROM execution. The Octal-SPI Flash Controller transfer the data either in a memory mapped direct fashion or in an indirect fashion where the controller is set up via configuration registers to silently perform some requested operation, signalling its completion via interrupts or status registers.
