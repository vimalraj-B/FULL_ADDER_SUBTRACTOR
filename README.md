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

FULL ADDER


![Full adder EXP 4 (3)](https://github.com/user-attachments/assets/c6cfe465-e813-42ac-9d43-3723d740a26a)


FULL SUBTRACTOR


![Full subtractor EXP 4 (3)](https://github.com/user-attachments/assets/fa3dbb52-4883-43dd-a709-a3af23aaddc1)

**Procedure**

Write the detailed procedure here

```

1).Type the program in Quartus software.

2).Compile and run the program.

3).Generate the RTL schematic and save the logic diagram.

4).Create nodes for inputs and outputs to generate the timing diagram.

5).For different input combinations generate the timing diagram

```

**Program:**
```

FULL ADDER

module fa(a,b,cin,sum,carry);
input a,b,cin;
output sum,carry;
assign sum=( (a ^ b)^c);
assign carry= ( (a & b)| ( cin &(a ^ b )));
endmodule

FULL SUBTRACTOR

module fs(a,b,bin,difference,borrow);
input a,b,bin;
output difference,borrow;
assign difference= ( (a ^ b)^bin);
assign borrow= ( ( a & b)| ( bin & ((a ^ b )));
endmodule

```

```

Developed by: B.VIMALRAJ.
Register Number:24900283.

```
**RTL Schematic**


FULL ADDER

![Full adder EXP 4](https://github.com/user-attachments/assets/d5f02dd3-cc66-495c-883d-8925c1cb4d2c)

FULL SUBTRACTOR

![Full subtractor EXP 4](https://github.com/user-attachments/assets/9adacc8d-6246-494c-b5d1-d2a3ded1a198)



**Output Timing Waveform**


FULL ADDER


![Full adder EXP 4 (2)](https://github.com/user-attachments/assets/a6c538cc-0c80-4a39-a60d-2b756323ca24)


FULL SUBTRACTOR


![Full subtractor EXP 4 (2)](https://github.com/user-attachments/assets/efe2f1da-9eca-4acf-bd0c-d98522d59cba)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



