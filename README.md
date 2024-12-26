# BOOLEAN_FUNCTION_MINIMIZATION

**Date**  1/10/2024

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

 Software – Quartus prime ,Cyclone V 

**Theory**
Boolean function minimization is the process of simplifying Boolean expressions, reducing the number of terms or literals without changing the functionality. Simplifying Boolean functions is essential for designing efficient digital circuits, as it reduces the number of gates required, minimizing cost, power consumption, and circuit complexity.

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Minimization**

F1

![WhatsApp Image 2024-12-21 at 08 56 19_1efb8ab4](https://github.com/user-attachments/assets/05574f4f-e972-4165-8809-1b61cde52511)

F2

![WhatsApp Image 2024-12-21 at 08 56 32_b98a0637](https://github.com/user-attachments/assets/b5a1bf45-b84a-4059-97aa-42b4a7455c27)

**Truth Table**

![Screenshot (102)](https://github.com/user-attachments/assets/29c0e26d-1230-4d5c-bdc2-f9d6b2a0c8d8)



**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

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

**RTL**
![ex-2 output 1](https://github.com/user-attachments/assets/587dc74b-2117-46e2-952a-1b3e4cfe4aeb)

![ex-2a output1](https://github.com/user-attachments/assets/be6a7736-6570-4c56-9395-6d6b4e55a403)

**Output:**
![ex-2 output 2](https://github.com/user-attachments/assets/f8e7ad71-fb73-4026-9286-372c5773fd5c)

![ex-2a output2](https://github.com/user-attachments/assets/0b77173e-b2b5-42e6-9142-2bc22e1b9adf)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

