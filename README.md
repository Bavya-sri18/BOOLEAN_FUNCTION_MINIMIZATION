# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**
Software – Quartus prime,Cyclone V

**Theory**

Boolean function minimization is the process of simplifying Boolean expressions, reducing the number of terms or literals without changing the functionality. Simplifying Boolean functions is essential for designing efficient digital circuits, as it reduces the number of gates required, minimizing cost, power consumption, and circuit complexity.

**Logic Diagram**

![WhatsApp Image 2024-11-12 at 14 18 00_75f9df83](https://github.com/user-attachments/assets/72cdf167-8c63-44ca-854d-e7c1e9a9b7fa)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900078 Bavya sri .B

```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**Output:**
![ex-2 output 2](https://github.com/user-attachments/assets/0a102115-6bdf-4026-b329-1b56afc339e4)
![ex-2a output2](https://github.com/user-attachments/assets/38054847-33f7-498b-bc10-45c0fab6dfe5)


**RTL**
![ex-2 output 1](https://github.com/user-attachments/assets/b2e3bb1c-2e7b-4fec-8677-2314dfc13768)
![ex-2a output1](https://github.com/user-attachments/assets/8b7f9f09-30ed-454c-8912-1683d5adc74f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

