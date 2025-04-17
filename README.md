### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: SANGEETHA S
 RegisterNumber: 212224040287
```
module ex1(a,b,c,d,e,f,g,h);
input a,b;
output c,d,e,f,g,h;
assign c=a&b;
assign d=a|b;
assign e=a^b;
assign f=~(a&b);
assign g=~(a|b);
assign h=~(a^b);
endmodule
 ```
**Logic symbol & Truthtable**

![Screenshot 2025-04-17 114038](https://github.com/user-attachments/assets/e892b72a-2ae6-4804-a167-7e1c0845c3cc)
![Screenshot 2025-04-17 114044](https://github.com/user-attachments/assets/4c6c6846-e85e-476a-aaab-08a4d06790c9)
![Screenshot 2025-04-17 114109](https://github.com/user-attachments/assets/6c923589-ef26-4853-a696-cf178c4dce9e)
![Screenshot 2025-04-17 114056](https://github.com/user-attachments/assets/6ba534d6-e1d7-4517-b902-3f845e69da28)
![Screenshot 2025-04-17 114050](https://github.com/user-attachments/assets/f188b96e-7d2c-4fa9-83e7-701b7456cd40)
![Screenshot 2025-04-17 114217](https://github.com/user-attachments/assets/7b9dff58-46ab-4cf1-a4ee-f9629ed858c5)








**RTL realization Output:** 

![Screenshot 2025-03-20 110501](https://github.com/user-attachments/assets/7a0cf143-0ca8-4840-ac05-8460f973c1d3)



**RTL**
![Screenshot 2025-03-20 104027](https://github.com/user-attachments/assets/199acdfa-b910-4845-8f60-b9e8a6cf200e)


**Result:**
Thus the program is verified and executed successfully.


