 Day 1 - C Programming and RV64 Data Types
* Set up the workspace environment inside vsd-riscv2 to run standard C programs.
* Created c1.c to compute the sum of integers from 1 up to 5 using a for loop.
* Compiled the program using gcc c1.c directly in the terminal
* Ran ./a.out and verified the correct calculation result of 15.
* Developed signed.c to test numeric boundary values for signed 64-bit data types.
* Included math.h library functions to calculate exponent values of 2^63.
* Handled doubleword bounds to demonstrate how 64-bit registers store signed integers in RISC-V architecture.
* Executed signed.c to display the exact integer limits on the screen.
* Confirmed the maximum limit of 9223372036854775807 (2^63 - 1).
* Confirmed the minimum limit of -9223372036854775808 (-2^63) for signed doublewords in RV64.