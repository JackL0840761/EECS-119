# EECS-119 4-Bit Up/Down Counter Design and Verification
This project focuses on the design, layout implementation, and rigorous physical verification of a 4-bit synchronous/asynchronous Up/Down Counter utilizing cascaded JK Flip-Flops. The entire workflow encompasses schematic design, custom layout generation, and full verification compliance to ensure accurate pre- and post-layout simulation results.

# Project Objectives
* **Schematic Design:** Implement a functioning 4-bit Up/Down counter by cascading individual custom-built JK Flip-Flops.
* **Component-Level Design:** Develop fundamental sub-blocks including 2-input and 3-input NAND gates (`NAND2`, `NAND3`), 2-input OR gates (`OR2`), and Inverters (`inverter-3`).
* **Physical Layout:** Create optimized layouts for all logic gates, the master-slave JK Flip-Flop, and the top-level 4-bit counter structure.
* **Verification & Sign-off:** Achieve 100% clean status across crucial physical verification steps:
  * **DRC (Design Rule Checking):** Ensure zero geometric or manufacturing rule violations.
  * **LVS (Layout Versus Schematic):** Guarantee structural equivalence and exact netlist matching between layout and schematic.

Repository Architecture     
├── 4 Bit Updown.pdf     
├── 4BIT_UPDOWN.zip     
├── master_slave_JKFF.zip     
├── NAND3_new.zip     
├── NAND2.zip     
├── OR2.zip     
└── inverter-3.zip     
