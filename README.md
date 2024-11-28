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


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24900616 Swetha.K
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```



**RTL**
![Screenshot (22)](https://github.com/user-attachments/assets/35341a36-d870-4724-ade4-4c668c79bb24)
![Screenshot (26)](https://github.com/user-attachments/assets/5ba56cb4-5466-48f0-83b2-b20041d15918)



**Timing Diagram**
![Screenshot (23)](https://github.com/user-attachments/assets/68f195d2-610b-41e5-9a9a-93d2ad64d357)
![Screenshot (27)](https://github.com/user-attachments/assets/ad623bc4-ce8c-49d6-a42b-5e2f8e3f09cd)
**Output**
![Screenshot (23)](https://github.com/user-attachments/assets/68f195d2-610b-41e5-9a9a-93d2ad64d357)
![Screenshot (27)](https://github.com/user-attachments/assets/ad623bc4-ce8c-49d6-a42b-5e2f8e3f09cd)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

