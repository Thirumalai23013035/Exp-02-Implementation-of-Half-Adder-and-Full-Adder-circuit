# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

![Screenshot 2023-11-26 144456](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/af1384f2-afdf-476c-98a7-89d5f067c17c)

/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: THIRUMALAI V

RegisterNumber:  23013035

*/
Logical Diagram

![WhatsApp Image 2023-11-27 at 21 37 10_ad9480d2](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/bca15133-5202-4022-9ce6-294464f5a2ff)

Truthtable

![Exp2 truthtable](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/bf648fb2-a0d3-4c06-87c2-499fb3a6ea6c)

### Output:
### RTL
### TIMING DIAGRAM

![Screenshot 2023-11-26 141011](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/32e65b7e-99c6-452c-b72d-be4f691a4955)

### TRUTH TABLE 

### Result:
