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


1 module DE02(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); endmodule 2 module DE2(w,x,y,z,f2); input w,x,y,z; output f2; assign f2=((~y & z)|( w & y )|(x & y)); endmodule /* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by:Girishva.K RegisterNumber:25009292


**RTL realization**
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/6b0ab2c5-4de4-4245-8bf3-6c94a88f7ef9" />

**Output:**
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/1b78b556-edfd-44d3-97ad-3dd2b0d71259" />

**RTL**
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/32dbfe00-56d7-4f8d-8e82-549a1320a2c4" />

**Timing Diagram**
<img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/3d196609-d456-4b59-8550-27accdeec123" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

