# RISC-V Processor Design
================================

## Overview
This project implements a RISC-V processor design using Verilog. The design includes a pipelined architecture with various components, including an Arithmetic Logic Unit (ALU), control unit, instruction memory, register file, and hazard unit.

## Files
### Processor Components

* **ALU.v**: 4-bit Arithmetic Logic Unit (ALU) performing arithmetic and logical operations.
* **ALU_Decoder.v**: ALU Decoder translating operation codes to ALU control signals.
* **Execute_Cycle.v**: Execute Cycle module integrating the ALU and ALU Decoder.
* **Fetch_cycle.v**: Fetch Cycle module responsible for fetching instructions from memory.
* **Hazard_Unit.v**: Hazard Unit detecting and resolving hazards in the pipeline.
* **Instruction_memory.v**: Instruction Memory storing program instructions.
* **Main_Decoder.v**: Main Decoder decoding instructions and generating control signals.
* **mem_file.mem**: Memory file containing program data and instructions.
* **Mux.v**: Multiplexer module used in various components.
* **PC.v**: Program Counter module managing instruction addresses.
* **Pipeline_Top.v**: Top-level module integrating all pipeline stages.
* **Register_File.v**: Register File storing processor registers.
* **Sign_Extend.v**: Sign Extension module used in instruction decoding.
* **Writeback_Cycle.v**: Writeback Cycle module writing results back to registers.

### Pipeline Stages

The processor design consists of the following pipeline stages:

1. **Fetch Cycle**: Fetches instructions from memory.
2. **Decode**: Decodes instructions and generates control signals.
3. **Execute**: Executes instructions using the ALU.
4. **Memory Access**: Accesses memory for load and store operations.
5. **Writeback**: Writes results back to registers.

## Usage
### Simulation

Use your preferred Verilog simulation tools (e.g., ModelSim, Vivado) to simulate the functionality of the processor.

### Synthesis

The modules can be synthesized for FPGA implementation using tools like Xilinx Vivado or Altera Quartus.

## Note
This project is a RISC-V processor design implementation in Verilog. It is intended for educational and research purposes only.
## Result 
![Picture1](https://github.com/user-attachments/assets/5aac79ed-8b34-46f5-9145-b733f9d5b3bb)

![Picture3](https://github.com/user-attachments/assets/42a1626e-c937-4b30-805f-05fbc44b69b8)
![Picture2](https://github.com/user-attachments/assets/ad81de1e-ef3e-433f-8bea-78ccb44835dd)
