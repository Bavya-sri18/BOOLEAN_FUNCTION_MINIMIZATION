# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**
software-quartus prime,cyclone V


**Theory**
Boolean function minimization is the process of simplifying Boolean expressions, reducing the number of terms or literals without changing the functionality. Simplifying Boolean functions is essential for designing efficient digital circuits, as it reduces the number of gates required, minimizing cost, power consumption, and circuit complexity.


**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900078 Bavya Sri .B
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
**Output:**
![ex-2 output 2](https://github.com/user-attachments/assets/05dcbf2b-0957-4f29-ae2b-2360e35f8a48)

**RTL**
![ex-2 output 1](https://github.com/user-attachments/assets/ba493898-c2fb-4a21-9f62-9fbcc7068e20)


**Timing Diagram**
![ex-2 output 2](https://github.com/user-attachments/assets/f413b3f1-3e56-4bb0-a4fe-5bd78fdfdc0d)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

