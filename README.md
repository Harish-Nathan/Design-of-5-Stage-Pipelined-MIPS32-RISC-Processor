# Design-of-5-Stage-Pipelined-MIPS32-RISC-Processor
This repository contains the details and the code for the MIPS32 ISA based RISC Processor, which is implemented in 5 stage pipelined configuration.
# Tabel-of-Conrent
▫️ MIPS32
▫️ Addressing Modes
▫️ Instructions considered
▫️ Instruction Encoding
▫️ Stages of Execution
▫️ Non Pipelined DataPath
▫️ Pipelined DataPath
▫️ Verilog Design Code
▫️ Example Program Testbench Code
▫️ EDAplayground Link
▫️ Known issues and problems
▫️ References
# MIPS32
32 x 32 bit GPRs [R0 to R31]
R0 hardwired to logic0
32 bit Program Counter (PC)
No flag registers (carry, zero, sign..etc)
Few Addresing Modes
Only Load and Store instructions can access memory
We assume memory word size is 32 bits (word addressable)
