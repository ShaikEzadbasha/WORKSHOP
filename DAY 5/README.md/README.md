Day 5 - Complete Single-Stage RV32I CPU Implementation and Simulation
* Built a complete single-stage RV32I core logic inside the Makerchip platform.
* Configured program counter generation using simple PC increment and branch target logic.
* Extracted source registers rs1 and rs2 alongside destination register rd using instruction field bits.
* Designed immediate field decoding logic for I, S, B, U, and J format instructions.
* Computed conditional branch signals using comparison operators inside taken branch logic.
* Evaluated branch target address br_tgt_pc by adding immediate offsets to current program counter.
* Executed arithmetic commands like ADD and ADDI directly inside ALU result generation block.
* Instantiated instruction memory and single-stage register file macros using m4+imem and m4+rf.
* Executed test routine summing numbers 1 through 9 inside register x10.
* Verified total execution flow using Makerchip visual block diagrams and signal waveform viewer.