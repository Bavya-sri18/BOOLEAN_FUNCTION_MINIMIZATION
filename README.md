# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

 Software – Quartus prime ,Cyclone V 

**Theory**
Boolean function minimization is the process of simplifying Boolean expressions, reducing the number of terms or literals without changing the functionality. Simplifying Boolean functions is essential for designing efficient digital circuits, as it reduces the number of gates required, minimizing cost, power consumption, and circuit complexity.


**Logic Diagram**

![WhatsApp Image 2024-11-12 at 14 18 06_df12b77b](https://github.com/user-attachments/assets/7a990cfd-e9c6-45c3-9e23-c832c9b52cdb)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Bavya Sri .B RegisterNumber: 24900078
i)
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
ii)
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**Output:**
![ex-2 output 2](https://github.com/user-attachments/assets/f8e7ad71-fb73-4026-9286-372c5773fd5c)

![ex-2a output2](https://github.com/user-attachments/assets/0b77173e-b2b5-42e6-9142-2bc22e1b9adf)

**RTL**
![ex-2 output 1](https://github.com/user-attachments/assets/587dc74b-2117-46e2-952a-1b3e4cfe4aeb)

![ex-2a output1](https://github.com/user-attachments/assets/be6a7736-6570-4c56-9395-6d6b4e55a403)

**Timing Diagram**
![ex-2 output 2](https://github.com/user-attachments/assets/a5342941-2a10-447e-b74b-ceb03adcfd56)

![ex-2a output2](https://github.com/user-attachments/assets/d408e513-4b7a-4688-a0d3-3372102e91c9)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

