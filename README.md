# simple-pipelined-processor

In this project a 4-stage pipelined processor is implemented with instruction set containing only three instructions addition (ADD), substraction (SUB), no operation(NOP). The four stages of the pipeline are :
- instruction fetch ( if )
- instruction decode ( id )
- execute ( ex )
- write back ( wb )

The processor takes clk, reset and 8-bit instruction, data_a, data_b as inputs and produces an 8-bit result and the designing is done in pipelined fashion. The module is designed in verilog hdl using Intel Quartus Prime software and is simulated with a testbench in Modelsim with test vectors covering all three operations.

This processor is only a simple representation to better understand the concept of pipelining, actual processors are more complex and include complete instruction set and have additional features like hazard mitigation techniques, branch prediction , etc,.
