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
## Half adder:
![Screenshot 2024-01-02 034221](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/eff59298-9165-40f8-8a86-cfe86c8692de)

## Full adder:


![Screenshot 2024-01-02 034229](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/05b0950a-de46-4c0b-9b17-5a64b20bd29c)


/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: R.Nandhana
RegisterNumber: 23005507 
*/
Logic symbol & Truthtable
RTL realization
##Halfadder

![Screenshot 2024-01-02 034301](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/8283c695-a8d4-4079-ac5e-9ea0afa905cc)

## Full adder

![Screenshot 2024-01-02 034310](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/a446217c-0ed2-4be4-b6aa-3cc8d268c220)



### Output:

![Screenshot 2024-01-02 034326](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/ddb424d7-905e-466e-af61-4be4b24b85c6)

![Screenshot 2024-01-02 034337](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/2d10afb9-ba4b-4be7-a3ea-5f04aba0ebd6)


##Truthtable:
Halfadder:

![Screenshot 2024-01-02 034238](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/4ce910d7-27b9-48f3-b028-bd65f03c1ddb)
Fulladder:

![Screenshot 2024-01-02 034251](https://github.com/Nandy-nan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/153698914/0a51e04f-9563-4588-b473-c59d1d797957)






### Result:
