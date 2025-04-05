# Complete-CPU
COE608 Lab 6 – Complete VHDL CPU Implementation
This project was completed as the final lab for the COE608: Computer Organization and Architecture course at Toronto Metropolitan University. The goal was to design and simulate a fully functional CPU by integrating the datapath, control unit, and a custom reset circuit, all written in VHDL.

# Features
- Complete CPU system in VHDL

- Custom synchronous reset circuit with timed startup behavior

- Integration of datapath, control unit, reset circuit, and instruction memory

- Support for core instructions such as ADD, LUI, etc.

- Verified through timing simulation

# What I Learned
- Designing and implementing reset logic in VHDL

- Modular CPU integration and simulation

- Interfacing VHDL components and memory modules

- Debugging using waveform outputs and timing diagrams

# Project Files
- datapath.vhdl – ALU, registers, and internal CPU data flow

- control_unit.vhdl – Instruction decoding and control signal generation

- reset_circuit.vhdl – Handles program counter reset and startup control

- cpu_top.vhdl – Top-level file integrating all components

- instruction_memory.mif – Instruction set for simulation
