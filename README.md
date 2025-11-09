# ALU
4-bit ALU ASIC design : RTL-coded, simulated, and synthesized using Cadence tools

# Arithmetic Logic Unit (ALU) — ASIC RTL Design

### Overview
This project implements a **4-bit Arithmetic Logic Unit (ALU)** in **Verilog HDL**, synthesized for ASIC implementation.  
The ALU performs basic arithmetic and logical operations using separate control and datapath modules.  
It was designed, simulated, synthesized, and analyzed using **Cadence tools**.

---

### Features
- 4-bit **Arithmetic and Logic** operations  
- Supports **Addition, Subtraction, AND, OR, XOR**  
- **Control–Datapath** separation for clean RTL design  
- Implemented as **Mealy-style RTL architecture**  
- Synthesizable and ready for ASIC implementation  
- Verified through simulation (functional + waveform)  
- Analyzed for **area, timing, and power** in Cadence Genus  
- Physical Design steps done in **Innovus** (floorplanning, placement, routing)  
- **Timing closure** and STA verification with **Tempus**

---

### Tools Used
- **Verilog HDL** — RTL design and testbench  
- **Cadence nclaunch** — Functional Simulation  
- **Cadence Genus** — Synthesis, area, timing  
- **Cadence Innovus** — Floorplanning, placement, routing  
- **Cadence Tempus** — Static timing analysis  

---

### 📎 File Structure
