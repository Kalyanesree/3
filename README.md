**Implementation-of-Half-Adder-and-Half Subtractor-circuit**

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![1](https://github.com/Kalyanesree/3/assets/163311552/6b298724-6298-46a9-a7b3-a92214cd82bb)


Figure -01 HALF ADDER

Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

Diff = A’B+AB’ =A ⊕ B Borrow = A’B


![2](https://github.com/Kalyanesree/3/assets/163311552/b1f768da-1ca6-48d0-b9f0-f73cd3c85ebb)


Figure -02 HALF Subtractor

Truthtable

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program:

![PROGRAM](https://github.com/Kalyanesree/3/assets/163311552/07ac8abe-dfe4-4809-a0c8-4d72c3cf0a5e)


Developed by: KALYANE SREE M    RegisterNumber: 212222050028

RTL Schematic

![5](https://github.com/Kalyanesree/3/assets/163311552/9898ac5b-b6ee-4a65-8a07-db30faee567d)

HALF SUBTRACTOR

![6](https://github.com/Kalyanesree/3/assets/163311552/d8dc809a-c068-48be-b554-a79f746ab6a5)
![7](https://github.com/Kalyanesree/3/assets/163311552/d6af4e97-86c9-475a-be00-2eace43152cd)


