# Analysis of CMOS based NAND Gate on 28 nm technology

This repository presents the design of NAND Gate implemented using Synopsis Custom Compiler on 28nm CMOS Technology.

# Introduction:
In Digital Design, a NAND gate is a logic gate which produces an output which is false only if all its inputs are true. NAND gate using CMOS will be designed using 2 PMOS and 2 NMOS devices. The 2 PMOS will be connected in parallel with each other and in series with the 2 NMOS. Inputs will be between the NMOS and PMOS pairs, and the output will be between the PMOS and NMOS connection. NAND Gate is an universal gate and is an important part of electronic circuits. This complete design and implementation is done using VLSI technology which has features such as high speed, low cost, small size and low power.

# Tools Used:

<b>• Synopsys Custom Compiler:</b></br>
&emsp;The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

<b>• Synopsys Primewave:</b></br>
&emsp;PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

<b>• Synopsys 28nm PDK:</b></br>
&emsp;The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# Pre-Layout Schematics and Simulations:

## Schematics:

### Differential Delay Cell:
Initially Schematic of the Differential Delay cell was implemented and converted into a symbol so that it could be used directly as delay cell from the library.
<p align="center">
  <img src=Images/circ.png></br>
  Fig. 4: Differential Delay Cell Schematic
</p>
<p align="center">
  <img src=Images/sim.png></br>
  Fig. 5: Differential Delay Cell Symbol
</p>



# Author:
• Aditya Agarwal, B.Tech(EEE), BITS Pilani KK Birla Goa Campus.

# Acknowledgements:
• <a href='https://www.iith.ac.in/events/2022/02/15/Cloud-Based-Analog-IC-Design-Hackathon/'>Cloud Based Analog IC Design Hackathon</a></br>
• <a href='https://www.synopsys.com/'>Synopsys India</a></br>
• <a href='https://www.vlsisystemdesign.com/'>VLSI System Design (VSD) Corp. Pvt. Ltd India</a></br>

# References:
[1] Balraj Singh, Mukesh Kumar, J. S. Ubhi. Analysis of CMOS based NAND and NOR Gates at 45 nm.</br>
[2] Kapil Mangla, Prof. (Dr.) Anil Kumar. Study and Analysis of NOT and NAND gate using various low power techniques.
