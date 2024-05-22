# 8-bit ALU Design and Verification Project

## Description
This project encompasses the design, implementation, and verification of an 8-bit Arithmetic Logic Unit (ALU) using Verilog. The ALU is capable of performing basic arithmetic operations such as addition, subtraction, increment, and decrement, along with bitwise logical operations including AND, OR, XOR, and shift operations. The ALU interfaces with registers A and B, storing input values and output results in the register RES. Additionally, flag generation mechanisms within the ALU indicate conditions such as zero, overflow, and underflow, enhancing the ALU's functionality.

## Verification Methodology
Universal Verification Methodology (UVM) code was also writtern for verification of the ALU design. The verification environment is structured using various SystemVerilog modules, including interface, agent, directed sequences, driver, environment, monitor, reference model, random sequences, scoreboard, testbench top, and transaction handling.
