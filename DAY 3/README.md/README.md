Day 3 - TL-Verilog Design and Pipelined Calculator in Makerchip
* Designed combinational and sequential calculator logic using TL-Verilog in Makerchip IDE.
* Implemented fundamental arithmetic operations including addition, subtraction, multiplication, and division.
* Utilized multiplexer selection logic based on operation code op[1:0] to route calculator outputs.
* Designed pipeline stages using @1 and @2 timing annotations for multi-cycle data flow.
* Added counter logic and valid signals to control conditional pipeline execution.
* Connected previous output feedback using state expression >>1$out and >>2$out for sequential operations.
* Implemented reset logic to initialize counter and clear output registers to zero.
* Simulated design execution and analyzed logic behavior through Makerchip block diagrams.
* Verified signal waveforms in the VIZ tab to observe dynamic data path transitions.
* Confirmed testbench completion criteria using cyc_cnt assertions for automated verification.