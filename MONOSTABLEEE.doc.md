            MONOSTABLE AND ASTABLE MULTIVIBRATOR 
                                   USING 555 TIMER

AIM:
       To design monostable and astable multivibrator using NE 555 timer.

APPARATUS REQUIRED:
  
  
S.NO	NAME OF THE EQUIPMENT	SPECIFICATION	NUMBER
    1.
    2.
  

 
    3.
    
    4. 
    5.
    
    6. 
    
    7.  
    8.	NE 555 timer
Resistors



Capacitor

CRO
AFO

RPS

Trainer kit
Connecting
wires
	
10KΩ
3.5KΩ
6.8KΩ

0.1  µf
0.01µf
20 MHz
  2 MHz

0-30 V
0-  2 A
  	  1
  1
  1
  1
  
  1
  1
  1
  1
  
  1




Capacitor

CRO
AFO

RPS

Trainer kit
Connecting
wires
	
10KΩ
3.5KΩ
6.8KΩ

0.1  µf
0.01µf
20 MHz
  2 MHz

0-30 V
0-  2 A
  	  1
  1
  1
  1
  
  1
  1
  1
  1
  
  1

Resistors



Capacitor

CRO
AFO

RPS

Trainer kit
Connecting
wires
	
10KΩ
3.5KΩ
6.8KΩ

0.1  µf
0.01µf
20 MHz
  2 MHz

0-30 V
0-  2 A
  	  1
  1
  1
  1
  
  1
  1
  1
  1
  
  1


SPECIFICATIONS:

          Maximum supply voltage     =  18 V
             Maximum power dissipation =  600 MW

DESIGN:

ASTABLE MULTIVIBRATOR:
                Vc = Vcc (1-e –t/RC)
The time taken by the circuit to change from 0 to 2/3 Vcc  is

              2/3 Vcc =Vcc(1-e–t/RC)
                     t1= 1.09 C;
 The time taken circuit to charge from 0 to 1/3 Vcc 
                1/3 Vcc= Vcc(1-e–t2/RC)
The time taken to charge from 1/3 Vcc to 2/3 Vcc is
                  ton = t1-t2
                  ton =0.69 RC;
                   R = RA+RB
                  ton =0.69(RA+RB)
 The time taken by the capacitor to discharge from 2/3 Vcc to 1/3 Vcc is         
                 toff=0.69RBC
Duty cycle, D= ton/(ton+toff)
Frequency  f = 1/т = 1/(ton+ toff)
Let              f =1 kHz; T = 1 ms;
For 75% duty cycle , 
               ton = 0.75ms;
               toff = 0.25ms;
               toff = 0.69 RBC;
let C = 0.1 µf;
               RB= 3.623*103 Ω
RB is selected as 3.5kΩ
             ton = 0.69(Ra+Rb)C
             RA = 7.246kΩ
RA is selected as 6.8kΩ     
       R is approximately taken as 10kΩ

MONOSTABLE MULTIVIBRATOR:
         
 The voltage across the capacitor is given by,
                                       Vc = Vcc  [1- e-t/RC]
Let t = T,  Vc =2/3 Vcc
       Tc =Rc ln
       T  =1.1Rc ms
       f   = 500 Hz ; T=1/f = 2 ms
       C = 0.1µf≤ duty cycle = 50%
       Ton =Toff =1 ms
       R=T/1.1 C = 10-3/1.1*10-6*0.1
       R= 9.09 kΩ
       R is approximately taken as 10kΩ

555 TIMER PIN DIAGRAM:
<img width="413" height="238" alt="image" src="https://github.com/user-attachments/assets/6a641408-3339-4893-8924-9a2b632af192" />


                












FUNCTIONAL DIAGRAM:
<img width="390" height="382" alt="image" src="https://github.com/user-attachments/assets/1df41a17-d169-49fe-b9a5-13e0f9689a30" />

              
                   





Astable Multivibrator
<img width="452" height="356" alt="image" src="https://github.com/user-attachments/assets/73efc7cf-7497-441e-b2f0-6d0d4a2f7a09" />





Monostable Multivibrator
<img width="474" height="352" alt="image" src="https://github.com/user-attachments/assets/0f1a395d-6923-46d1-8bb6-65999515ecc5" />




PROCEDURE:

MONOSTABLE MULTIVIBRATOR:
          
                The circuit connections are made as shown in the circuit diagram. AFO input of desired frequency is given to input pin of 555 timer. The Multivibrator output of the required period is seen in CRO connected to output pin of 555 timer.
        The capacitor voltage waveform is also seen in CRO by connecting to pin 6. The magnitude of the waveform and time period of the wave form are noted 

ASTABLE MULTIVIBRATOR:

The circuit connections are made as shown in the figure. The case of astable multivibrator there is no need for triggering input; hence pins 2 and 6 are shorted. Based on he required duty cycle values resistance and capacitor are designed. The output of the astable multivibrator is seen in CRO. The magnitude and the time period of the waveforms are also noted.
 




THEORY:

555 AS MONOSTABLE MULTI VIBRATOR:

This circuit diagram shows how a 555 timer IC is configured to function as a basic monostable multivibrator.  A monostable multivibrator is a timing circuit that changes state once triggered, but returns to its original state after a certain time delay.  It got its name from the fact that only one of its output states is stable.  It is also known as a 'one-shot'. 
    
In this circuit, a negative pulse applied at pin 2 triggers an internal flip-flop that turns off pin 7's discharge transistor, allowing C1 to charge up through R1. At the same time, the flip-flop brings the output (pin 3) level to 'high'.  When capacitor C1 as charged up to about 2/3 Vcc, the flip-flop is triggered once again, this time making the pin 3 output 'low' and turning on pin 7's discharge transistor, which discharges C1 to ground. This circuit, in effect, produces a pulse at pin 3 whose width t is just the product of R1 and C1, i.e., t=R1C1.
    
The reset pin, which may be used to reset the timing cycle by pulling it momentarily low, should be tied to the Vcc if it will not be used.   


555 AS  ASTABLE MULTIVIBRATOR:
     This circuit diagram shows how a 555 timer IC is configured to function as an astable multivibrator.  An astable multivibrator is a timing circuit whose 'low' and 'high' states are both unstable.  As such, the output of an astable multivibrator toggles between 'low' and 'high' continuously, in effect generating a train of pulses. This circuit is therefore also known as a 'pulse generator' circuit.
    
In this circuit, capacitor C1 charges through R1 and R2, eventually building up enough voltage to trigger an internal comparator to toggle the output flip-flop.  Once toggled, the flip-flop discharges C1 through R2 into pin 7, which is the discharge pin.  When C1's voltage becomes low enough, another internal comparator is triggered to toggle the output flip-flop. This once again allows C1 to charge up through R1 and R2 and the cycle starts all over again.
      
C1's charge-up time t1 is given by: t1 = 0.693(R1+R2)C1. C1's discharge time t2 is given by: t2 = 0.693(R2)C1.  Thus, the total period of one cycle is t1+t2 = 0.693 C1(R1+2R2).  The frequency f of the output wave is the reciprocal of this period, and is therefore given by: f = 1.44/(C1(R1+2R2)), wherein f is in Hz if R1 and R2 are in megaohms and C1 is in microfarads.   


RESULT:
     Thus the monostable and astable multivibrator is designed for given frequency using NE 555 timer and the graph is plotted.

