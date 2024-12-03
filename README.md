# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot (98)](https://github.com/user-attachments/assets/221d7b48-69f1-403a-9d45-74d04d088913)

![Screenshot (97)](https://github.com/user-attachments/assets/9b71382d-abe8-430e-bb2e-936746aa9378)



**Procedure**

Write the detailed procedure here

Step1: Define the specifications and initialize the design.

Step2: Declare the name of the entity and architecture by using VHDL source code.

Step3: Write the source code in VERILOG.

Step4: Check the syntax and debug the errors if found, obtain the synthesis report.

Step5: Verify the output by simulating the source code.

Step6: Write all possible combinations of input using the test bench.

Step7: Obtain the place and route report.

**Program:**

 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
 
 Developed by:HARINI S
 
 RegisterNumber:24900110


**RTL Schematic**
![Screenshot (96)](https://github.com/user-attachments/assets/967baafd-bb9c-4c09-8ce9-98a6ba1e924c)

![Screenshot (94)](https://github.com/user-attachments/assets/aef8be9f-1db0-438f-9bc1-c7a7de4eabda)



**Output Timing Waveform**
![Screenshot (95)](https://github.com/user-attachments/assets/04bc19f7-85b8-423c-8cab-4bbc95cfd589)

![Screenshot (93)](https://github.com/user-attachments/assets/7d511d4c-09bc-4b0e-ba6c-e024fc6d47a2)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



