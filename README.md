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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: SAJITH AHAMED F
RegisterNumber: 23000083
*/
Logic symbol & Truthtable
RTL realization

### Output:
### HALF ADDER:
![HALF](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/e53200cb-2030-429c-89e6-127ccbace61c)
### FULL ADDER:
![FULL ADDER](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/51dc185f-6759-49b4-8e7e-d9079e9d4383)


### RTL
### HALF ADDER:
![HALF ADDER DIAGRAM](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/40b6887e-7ce5-46bb-850f-d354151059d1)
### FULL ADDER:
![FULL SUBTRACTOR-DIAGRAM](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/160312e9-f5cd-4a4d-b068-5ba02d009796)

### TIMING DIAGRAM
### HALF ADDER:
![HALF ADDER WAVEFORM](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/9b75a466-6e8c-462a-864c-f7155eff77f4)
### FULL ADDER:
![FULL ADDER-WAVEFORM](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/2ef9fc9f-74df-4512-9d66-76f31bd5c254)


### TRUTH TABLE 
### HALF ADDER:
![Screenshot 2023-11-28 141806](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/16e99b30-985f-4cb2-85b1-8b462425667f)

### FULL ADDER:
![Screenshot 2023-11-28 141759](https://github.com/Sajith-28/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149937471/87b2d30c-8313-4cc6-b92c-523e9d726772)


### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
