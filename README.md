# 8-bit-ALU-design-

An Arithmetic Logic Unit (ALU) is a core component of a CPU, responsible for performing arithmetic and logic operations. This Verilog-based project implements an 8-bit ALU capable of executing multiple operations such as addition, subtraction, AND, OR, XOR, NOT, shift left, and shift right.

 Features

8-bit inputs: A, B

4-bit select line to choose among operations

Supported operations:

0000: Addition (A + B)

0001: Subtraction (A - B)

0010: Bitwise AND (A & B)

0011: Bitwise OR (A | B)

0100: Bitwise XOR (A ^ B)

0101: Bitwise NOT (~A)

0110: Shift Left (A << 1)

0111: Shift Right (A >> 1)

Output: 8-bit Result, 1-bit Zero flag
