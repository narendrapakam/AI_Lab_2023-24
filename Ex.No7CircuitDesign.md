Ex.No: 7 Logic Programming – Logic Circuit Design
DATE: 01-04-2025
REGISTER NUMBER : 212222060171
AIM:
To write a logic program to design a circuit like half adder and half subtractor.

Algorithm:
Start the Program
Design a AND gate logic if both inputs are 1 then output is 1.
Design a OR gate logic if any one of input is 1 then output is 1.
Design a XOR gate logic if both inputs are different then output is 1.
Design a NOT gate logic if input is 0 then output is 1.
Design a half adder and half subtractor using the rules.
Test the logic.
Stop the program.
Program:
and(0,0,0).
and(0,1,0).
and(1,1,1).
and(1,0,0).
or(0,0,0).
or(0,1,1).
or(1,0,1).
or(1,1,1).
xor(0,0,0).
xor(0,1,1).
xor(1,0,1).
xor(1,1,0).
not(0,1).
not(1,0).
halfadder(A,B,S,C):-
    xor(A,B,S),
    and(A,B,C).
halfsubtractor(A,B,Diff,Bo):-
    xor(A,B,Diff),
    not(A,X),
    and(B,X,Bo).
Output:
image

Result:
Thus the truth table of circuit verified sucessfully.
