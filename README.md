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

![95afa0dc-6b79-4fc2-ab13-831b4f589dfa](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/aae3d54b-16e6-40e8-8a8d-18afd6b23105)


![1903d36b-79f1-4c07-a86f-8dfdff099b50](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/509ad84a-6220-4860-b2ae-42ef73641ef7)

 
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: THIRUMALAI V

RegisterNumber:  23013035

*/
 
 
Truthtable

 
### Output:
### RTL reilazation 

![fe1f3e2c-f1c5-4985-8e85-2db19cdef0b6](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/a4e385af-7ad1-4c8c-bad9-d762784d9f59)

![772cb5a2-866c-4ebe-a2f1-4dd12e350adb](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/414685d7-b2bd-4ba7-b092-862e5aa13a92)



### TIMING DIAGRAM

![160e1dc9-7744-42f2-9df1-692c356739ed](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/fc25a761-4aa8-4180-be55-34820e77b488)



![7795943b-f76b-4372-b1e8-9bb8de9aac52](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/b1d8d869-af1c-4571-ba24-a302d4c52370)

 
### TRUTH TABLE 

![602b173f-0154-4e88-a3fc-e00de07b56f3](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/33f70e74-5db3-47bc-a098-bf859964f77a)

![883296cb-0a03-4802-a3d5-4e54cd7f1882](https://github.com/Thirumalai23013035/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153185249/a4217c0a-30f6-4979-a2f8-2460b9eb2b2c)




### Result:
 Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus using
Verilog programming.
