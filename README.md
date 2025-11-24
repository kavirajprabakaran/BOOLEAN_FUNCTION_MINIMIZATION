AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Theory

Logic Diagram

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program:

module exp2(a,b,c,d,w,x,y,z,f1,f2); input a,b,c,d,w,x,y,z; output f1,f2; assign f1=((~b&~d)|(~a&b&d)|(a&b&~c)); assign f2=((~y&z)|(w&y)|(x&y)); endmodule

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: KAVIRAJ.P RegisterNumber: 25017431

RTL realization Timing Diagram

Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
