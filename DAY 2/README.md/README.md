Day 2 - RISC-V Assembly Language and C Interface
* Explored ABI function call conventions using assembly and C program integration.
* Created load.s assembly file containing arithmetic loop logic and register moves.
* Developed sum1_9.c driver program declaring external function reference load().
* Passed parameters using RISC-V argument registers a0 to a2 for loop execution.
* Handled conditional branching with blt instruction to control iteration state inside the assembly loop.
* Updated loop variables incrementally using addi instruction in assembly.
* Executed basic register assignments using add instructions with zero register.
* Returned computed summation result through register a0 back to C printf call.
* Linked C driver code with assembly subroutines using RISC-V GCC cross-compiler.
* Verified proper assembly function execution and register parameter passing in terminal output.