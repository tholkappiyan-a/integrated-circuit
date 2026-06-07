HALF/FULL ADDER & HALF/FULL SUBTRACTOR
 
Aim:
To realize half/full adder and half/full subtractor.
i.Using X-OR and basic gates.
ii.Using only NAND gates. 
Apparatus Required:
Digital Trainer Kit, IC 7486, IC 7432, IC 7408, IC 7400, and connecting wires
Procedure: 
	1.Verify the gates.
2.Make the connections as per the circuit diagram.
3.Switch on VCC and apply various combinations of input according to               the truth table.
4.Note down the output readings for half/full adder and half/full subtractor sum/difference and the carry/borrow bit for different combinations of inputs.

Half Adder using basic gates:-
<img width="438" height="204" alt="image" src="https://github.com/user-attachments/assets/5e0e9a3e-fd1c-4d16-bf5f-ab0c8ed0f5d2" />






Full Adder using basic gates:-
<img width="780" height="267" alt="image" src="https://github.com/user-attachments/assets/f9154ab7-3376-4031-a497-1f24935b7a54" />











Half Adder using NAND gates only:-
<img width="780" height="250" alt="image" src="https://github.com/user-attachments/assets/f88d96ad-89c5-4e7a-9f07-3d9c0cce02c1" />










Full Adder using NAND gates only:-
<img width="780" height="215" alt="image" src="https://github.com/user-attachments/assets/a26b82b7-c9ae-4cce-ba4d-f35bae15479d" />











Half subtractor Using only NAND gates:-
<img width="780" height="259" alt="image" src="https://github.com/user-attachments/assets/2a48e40a-ad99-4d85-a0d0-893c9ed016ca" />








Full Subtractor Using only NAND gates:-
<img width="780" height="217" alt="image" src="https://github.com/user-attachments/assets/1d45695a-ac82-4a12-b40f-71bb052ed54b" />










Half Adder
A	B	S	C	S(V)	C(V)
 0	0	0	0	0	0
0	1	1	0	1	0
1	0	1	0	1	0
1	1	0	1	0	1
         


 





Full Adder
A	B	Cn-1	S	C	S(V)	C(V)
0	0	0	0	0	 0	0
0	0	1	1	0	1	0
0	1	0	1	0	 1	0
0	1	1	0	1	0	1
1	0	0	1	0	1	0
1	0	1	0	1	0	1
1	1	0	0	1	0	1
1	1	1	1	1	1	1

 






Half Subtractor
A	B	D	B	D(V)	B(V)
0	0	0	0	 0	0
0	1	1	1	1	1
1	0	1	0	1	0
1	1	0	0	0	0

Full Subtractor
A	B	Cn-1	D	B	D(v)	B(v)
0	0	0	0	0	 0	 0
0	0	1	1	1	 1	 1
0	1	0	1	1	1 	1 
0	1	1	0	1	 0	 1
1	0	0	1	0	 1	 0
1	0	1	0	0	 0	 0
1	1	0	0	0	0 	 0
1	1	1	1	1	 1	1 









RESULT:
The truth tables and operation of half/full adder and half/full subractor circuits were successfully verified using logic gates.
