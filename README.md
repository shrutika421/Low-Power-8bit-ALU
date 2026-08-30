# 8-Bit Low-Power ALU Design Using VLSI Techniques

## Overview
This project implements an 8-bit Arithmetic Logic Unit (ALU) designed with Verilog HDL. To optimize dynamic power consumption—a key VLSI design objective—the design integrates **clock-gating techniques** that disable internal registers when the unit is idle.

## Key Features
* **8 Operations:** Addition, Subtraction, AND, OR, XOR, NOT, Shift Left, Shift Right.
* **Low-Power Optimization:** Integrated clock-gating control (`enable` signal) to freeze flip-flops during inactive cycles.
* **Flag Outputs:** Dynamic `carry_out` and `zero_flag` calculation.
* **Verification:** Fully tested using a dedicated Verilog testbench.

## Project Structure
* `alu_8bit.v` - Main Verilog module with clock-gating logic.
* `tb_alu_8bit.v` - Testbench for behavioral simulation.

## Simulation & Tools
* **Language:** Verilog HDL
* **Simulation Tools:** ModelSim
