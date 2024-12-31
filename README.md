# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

software-Quartus prime
**Software – Quartus prime**
cyclone V verilog program.

**Theory**
Boolean function minimization refers to the process of simplifying a Boolean expression to its most efficient form. The goal is to reduce the number of logic gates, variables, and terms needed to represent the function, which is important for hardware design and optimization in digital circuits.

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Minimization**

F1
![WhatsApp Image 2024-12-27 at 10 26 10_ca9c4705](https://github.com/user-attachments/assets/9f58f1a2-4593-495c-96ff-d067e3ba5d4f)
F2
![WhatsApp Image 2024-12-27 at 10 26 26_27ebb691](https://github.com/user-attachments/assets/2f6fb486-ee45-45ee-9491-2138dafcf853)

**Truth Table**

![WhatsApp Image 2024-12-27 at 10 26 45_3172d564](https://github.com/user-attachments/assets/4b0bfce6-a426-4498-b67f-f2dc1ec589ef)

**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Swetha.K  RegisterNumber: 24900616 
```
1.
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

2.
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL**

F1
![WhatsApp Image 2024-12-27 at 10 27 15_0dc383c0](https://github.com/user-attachments/assets/95c9cf66-b259-4c73-bed0-771bcfd44931)
F2
![WhatsApp Image 2024-12-31 at 12 39 37_e839c335](https://github.com/user-attachments/assets/36c1234c-4355-477d-99e0-bcb2d0f0ab0f)


**Output**

F1
![WhatsApp Image 2024-12-27 at 10 28 04_7c2d2e26](https://github.com/user-attachments/assets/b5707ac0-a434-4408-a57a-7273a18f9ea6)
F2
![WhatsApp Image 2024-12-27 at 10 28 25_f1fc549f](https://github.com/user-attachments/assets/c18ae005-6295-4895-9c65-451add5e5222)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

