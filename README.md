# 🧮 4-Bit Arithmetic Logic Unit (ALU)

### Overview

This project implements a **4-bit Arithmetic Logic Unit (ALU)** in Verilog HDL.
The design supports basic arithmetic and logical operations, verified through simulation and synthesized for ASIC implementation.


### Features
---
- **4-bit inputs (A, B)** and **3-bit opcode** control
-  Supports the following operations:
  * `000` → Addition
  * `001` → Subtraction
  * `010` → Multiplication
  * `011` → Division (with zero-check handling)
- 8-bit output (Result) for arithmetic precision
- Carry and Zero flag generation

### Repo Structure
---
├──Verilog: module and testbench files<br>
├──Imp outputs: SPEF, GDS, map, files<br>
├──Constraints: sdc file, template.tcl, setup.g file<br>
├──imp reports: area, time, power, gates report and output waveform<br>

### Tools Used
---
- **Cadence Genus** – Logic Synthesis
- **Cadence Innovus** – Physical Design
- **Virtuoso** – Layout and Verification
- **NC Launch / Xcelium** – Functional Simulation

### Reports Included
---
- Waveform ouput and netlist
- Area Report: Cell and total area utilization
- Gate Report: Logic cell breakdown
- Power Report: Estimated dynamic and leakage power
- Pre-timing Report: Delay summary prior to routing
