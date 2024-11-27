# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher



**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:Nidishkumar S
RegisterNumber:24002777
module experiment2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module experiment2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL realization**
![k](https://github.com/user-attachments/assets/e0e5ddc4-e4b1-44a0-bd28-f5cefe899652)

![WhatsApp Image 2024-11-27 at 13 45 18_d34e8cbf](https://github.com/user-attachments/assets/136713b6-2e6e-4114-9cda-10771a3d5a2f)





**Timing Diagram**
![WhatsApp Image 2024-11-27 at 13 45 19_3884be46](https://github.com/user-attachments/assets/1c789023-79db-458f-9120-e1d6288cb20f)

![WhatsApp Image 2024-11-27 at 13 45 18_98996925](https://github.com/user-attachments/assets/9865c7ac-a67c-42e3-bf28-370a6e10d88d)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

