Day 4 - RISC-V CPU Core Microarchitecture and Pipelined Microarchitecture
* Designed a 5-stage pipelined RV32I RISC-V CPU core using TL-Verilog in the Makerchip environment.
* Implemented instruction fetch logic with program counter incrementing and instruction memory access.
* Built instruction decoder blocks to parse R, I, S, B, U, and J instruction formats.
* Extracted opcode, funct3, funct7, and register specifiers along with immediate sign extension logic.
* Integrated 32-bit 2-read and 1-write port register file macro for register operand access.
* Constructed arithmetic logic unit supporting branch evaluation and register bypass data forwarding.
* Handled control hazards caused by taken branches using target PC calculation and valid signals.
* Added data memory interface with dmem macro for store (SW) and load (LW) operations.
* Loaded a test program calculating the sum of numbers from 1 to 9 into instruction memory.
* Simulated the core in Makerchip, verifying waveform timing and assembly execution in VIZ view.