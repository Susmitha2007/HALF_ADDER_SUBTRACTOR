# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
![WhatsApp Image 2024-12-02 at 10 27 58 AM](https://github.com/user-attachments/assets/0ad13e0d-9642-4af5-8bdf-0545d9b8c3ad)
![WhatsApp Image 2024-12-02 at 10 29 29 AM](https://github.com/user-attachments/assets/ade28988-0582-47b6-85cc-a33628e42c19)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Nara Guna Susmitha RegisterNumber:24010204

![Screenshot 2024-12-04 182505](https://github.com/user-attachments/assets/0ba7d5a0-cd8c-4b89-9766-64cebbf7fa16)

*/

**RTL Schematic**
![Screenshot 2024-12-02 101401](https://github.com/user-attachments/assets/771e4c8e-e288-4ac7-9358-d60bb54e1da0)
![Screenshot 2024-12-02 102455](https://github.com/user-attachments/assets/6b6d747e-8bbb-47ab-8050-ede4abf0061b)


**Output/TIMING Waveform**
![Screenshot 2024-12-02 101450](https://github.com/user-attachments/assets/a5bae70a-6f77-4251-a27b-79a8ca3d3157)
![Screenshot 2024-12-02 102235](https://github.com/user-attachments/assets/7939e92d-5945-4d30-813d-8c8519fba704)


**Result:**
Thus the half adder and half subtractor circuits,were successfully designed,and their truth tables were verified in 
Quaters using verilog programming
