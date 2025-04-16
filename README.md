# CODTECH-TASK3
Name - Yogita Shrikant Dhonge
Company - CODETECH IT SOLUTIONS
ID - CT04WM47
Domain -VLSI
Duration -March 18th,2025 to April 18th,2025
Mentor - Vaishali

Project Overview: 4-Stage Pipelined Processor Design

Objective

Design and simulate a 4-stage pipelined processor that supports basic instructions like ADD, SUB, and LOAD. You are expected to demonstrate how each instruction passes through the pipeline stages.


---

1. Pipeline Stages

A typical 4-stage pipeline includes the following stages:

1. Instruction Fetch (IF):

Fetch the instruction from memory.

Update Program Counter (PC).



2. Instruction Decode (ID):

Decode the instruction.

Read source registers.



3. Execute (EX):

Perform arithmetic/logical operations.

Compute effective address for LOAD.



4. Memory Access / Write Back (MEM/WB):

For LOAD, access memory and load data into register.

For ADD/SUB, write the result back to destination register.





---

2. Supported Instructions

ADD Rd, Rs1, Rs2: Rd = Rs1 + Rs2

SUB Rd, Rs1, Rs2: Rd = Rs1 - Rs2

LOAD Rd, [Rs1 + offset]: Rd = Memory[Rs1 + offset]



---

3. Key Components to Implement

Register File

ALU (Arithmetic Logic Unit)

Instruction Memory

Data Memory

Pipeline Registers (between each stage)

Control Unit (for decoding and control signal generation)



---

4. Simulation Deliverable

You’ll need to simulate the pipeline showing:

What instruction is in which stage at each clock cycle.

How data flows through pipeline registers.

Any data hazards and how they are managed (optional basic hazard handling like stalling or forwarding can be added for extra value).



---

5. Tools You Can Use

Verilog/VHDL with a simulator like ModelSim, Vivado, or Icarus Verilog

Or a C++/Python-based simulator (if HDL is not required)



---

Final Deliverable

Functional processor simulation showing 4 pipeline stages.

Test cases showing execution of ADD, SUB, LOAD.

Documentation or report explaining your design.

(Optional) Screenshots or waveform outputs of simulation.
