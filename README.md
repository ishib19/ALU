# 🧮 4-Bit Arithmetic Logic Unit (ALU)

### Overview

This project implements a **4-bit Arithmetic Logic Unit (ALU)** in Verilog HDL.
The design supports basic arithmetic and logical operations, verified through simulation and synthesized for ASIC implementation.

---

### Features

* **4-bit inputs (A, B)** and **3-bit opcode** control
* Supports the following operations:
  * `000` → Addition
  * `001` → Subtraction
  * `010` → Multiplication
  * `011` → Division (with zero-check handling)
* 8-bit output (Result) for arithmetic precision
* Carry and Zero flag generation

### 📂 Project Structure
ALU/
│
├── verilog/
│   ├── alu.v          # RTL design
│   ├── alu_tb.v       # Testbench
│
├── constraints/
│   ├── constraints1.sdc
│   ├── setup.g
│   ├── template.tcl
│
├── imp reports/
│   ├── ALU_area.rpt
│   ├── ALU_gates.rpt
│   ├── ALU_prelim.rpt
│   ├── ALU_Power_rep.png
│   ├── ALU_Netlist.png
│   └── ALU4OPFINAL.png
│
├── alu.gds             # Final layout (GDSII)
├── ALU.spef            # Parasitic extraction
└── streamOut.map       # Stream output mapping


### 🧠 Tools Used
* **Cadence Genus** – Logic Synthesis
* **Cadence Innovus** – Physical Design
* **Virtuoso** – Layout and Verification
* **NC Launch / Xcelium** – Functional Simulation

### Reports Included
*Waveform ouput and netlist
*Area Report: Cell and total area utilization
*Gate Report: Logic cell breakdown
*Power Report: Estimated dynamic and leakage power
*Pre-timing Report: Delay summary prior to routing
