OCTAL TO BINARY ENCODER
AIM:

To realise and verify the truth table of octal to binary encoder using IC74148 digital IC.
APPARATUS REQUIRED:

S.no	Name of the equipment	Specification	No.of quantity
1.	8X3 encoder	IC 74148	1
2.	Trainer kit		1
3.	Connecting wires		

PIN CONFIGURATION :
<img width="495" height="433" alt="image" src="https://github.com/user-attachments/assets/88a71b98-4c92-4114-b245-f028aaa22a6f" />

Fig.1

<img width="631" height="341" alt="image" src="https://github.com/user-attachments/assets/86738487-d7d7-4698-9015-bc19bb373ef9" />

<img width="524" height="530" alt="image" src="https://github.com/user-attachments/assets/a181ad61-4928-4f09-85ca-64ff438851fb" />






THEORY
An encoder is a digital function that produces reverse operation from that of a decoder. An encoder has 2^n input lines and n corresponding binary numbers. It is constructed with OR gates.
The encoder assume that only one input lines can be equal to 1 at any time
,otherwise the circuit has no meaning.The circuit has 8 inputs and can have 2^8=256 possible input combination. Only 8 of these combination are in "dont care" condition. This type of encoder available in IC form is called priority encoder. The circuit has active low inputs and active low outputs. The enable input and carry outputs which are also active low are used to cascade circuits which are used to handle more inputs.

PROCEDURE:

The connections are given as shown in the pin diagram. The inputs are given to the corresponding pin as in the truth table and the outputs are verified.

RESULT:
Thus the truth table of octal to binary encoder is realised and verified using IC 74148 .
