# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher


**Theory**
![WhatsApp Image 2024-10-22 at 10 36 06_688aa1d6](https://github.com/user-attachments/assets/d83e9ed3-1bcd-4894-861c-607970aa78ae)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by: DINESH PRABHU S
RegisterNumber: 24004388


**RTL realization Output:**
![Screenshot (66)](https://github.com/user-attachments/assets/860fcd6a-d1bb-4f27-a8a1-890c9efc5f20)

**Timing Diagram**
![Screenshot (67)](https://github.com/user-attachments/assets/305fb82d-4226-434b-ba88-ec0320f179ca)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

