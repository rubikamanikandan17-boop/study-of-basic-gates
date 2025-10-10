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

 Developed by: RegisterNumber: 25008774
 
 ## GATE LEVEL MODEL

![WhatsApp Image 2025-10-10 at 10 33 22_7c991a81](https://github.com/user-attachments/assets/c9c62916-dee9-4e94-9352-af892f505748)

## DATA FLOW  MODEL

![WhatsApp Image 2025-10-10 at 10 33 13_d5122493](https://github.com/user-attachments/assets/2ce82379-8a9d-40ae-b890-646bf7da113e)

 
**Logic symbol & Truthtable**
![WhatsApp Image 2025-10-10 at 10 11 55_5d8674d9](https://github.com/user-attachments/assets/a2b19251-cf0f-4835-a79f-a2e1bfd38470)


**RTL realization Output:** 

![WhatsApp Image 2025-10-10 at 10 11 54_5bf9ef61](https://github.com/user-attachments/assets/b4b6b188-3f5d-4cb7-83e9-cb695c30e809)


**RTL**

![WhatsApp Image 2025-10-10 at 10 11 54_4a7994d5](https://github.com/user-attachments/assets/ad79b819-8191-460c-bbca-f18a08b85c8b)

![WhatsApp Image 2025-10-10 at 10 11 54_0b41a897](https://github.com/user-attachments/assets/5dee56cb-5514-4093-b94c-27ecf989c9e9)


**Result:**

The truth tables of AND, OR, and NOT gates were successfully verified using Verilog code in Quartus Prime. The simulated outputs matched the expected values.



