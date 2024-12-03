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
![sum exp 4](https://github.com/user-attachments/assets/ebd05044-f549-4dae-824b-a1ae451752f0)
![subtracter exp 4](https://github.com/user-attachments/assets/89dc086f-9ac0-47d7-bcc6-f532e4398fa8)

**Procedure**

Write the detailed procedure here

![Screenshot 2024-12-03 135850](https://github.com/user-attachments/assets/5216ea26-b3fe-491b-9349-74c0373ac1e4)


**Program:**

![Screenshot 2024-12-03 135749](https://github.com/user-attachments/assets/3a3a3f96-102c-401c-8bc3-550e8ff87875)


Developed by: B.VIMALRAJ.
Register Number:24900283.

**RTL Schematic**

FULL ADDER:

![logic gate exp 4](https://github.com/user-attachments/assets/5b85de61-e151-43cf-bcec-69029fa0a02b)
FULL SUBTRACTOR:

![logic gate  exp 4](https://github.com/user-attachments/assets/1a0e5602-e4bc-4fc1-b5ab-7fb045385d20)

**Output Timing Waveform**
FULL ADDER:

![Full adder exp 4](https://github.com/user-attachments/assets/556b28f6-d796-48a9-8f5f-52333bc5d467)

FULL SUBTRACTOR:
![full sub exp 4](https://github.com/user-attachments/assets/9a411f2e-9e12-4c01-8cfb-ec5725955485)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



