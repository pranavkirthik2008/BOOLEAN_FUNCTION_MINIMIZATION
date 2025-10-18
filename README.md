# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
i) 
module funct1(a,b,c,d,f1); input a,b,c,d; output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
 ii) 
module funct2(w,x,y,z,f2); input w,x,y,z; output f2; 
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: PRANAV KIRTHIK 
RegisterNumber:*/ 25011678


**RTL realization**

**Output:**
![boolean mmb 1](https://github.com/user-attachments/assets/560d4321-71fc-4ab4-9790-7c6bf2c55c23)
![boolean mmb2](https://github.com/user-attachments/assets/31ea0168-6237-455b-9a28-4bfd09e29cf7)

**RTL**

**Timing Diagram**
![boolean mmb3](https://github.com/user-attachments/assets/dbe8e444-ff43-4987-bd21-bb79ba7d7f6f)
![boolean mmb4](https://github.com/user-attachments/assets/0428808a-08e1-4161-a06f-83cc96668551)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

