
INTEGRATOR AND DIFFERENTIATOR USING OP-AMP

AIM

To design and set up an integrator and differentiator circuit using op-amp.

APPARATUS REQUIRED

Power supply, CRO, function generator, bread board, op-amp, capacitor and resistors.

THEORY

INTEGRATOR

Refer to the figure 1. This circuit performs the integration of the input waveform. The

INTEGRATOR AND DIFFERENTIATOR USING OP-AMP

AIM

To design and set up an integrator and differentiator circuit using op-amp.

APPARATUS REQUIRED

Power supply, CRO, function generator, bread board, op-amp, capacitor and resistors.

THEORY

INTEGRATOR

Refer to the figure 1. This circuit performs the integration of the input waveform. The

output voltage 𝑉𝑜

can be expressed as	𝑉𝑜

= − 1
𝑅𝐶

∫ 𝑉𝑖𝑑𝑡 + 𝑘 where k is the constant of

integration which depends upon the value of 𝑉𝑜 at t = 0. The peak of the output waveform 𝑉𝑇

is given by the expression 𝑉𝑇

=  𝑉𝑇 , where T is the time period of the input square wave.
4𝑅𝐶

Integrators are commonly used in analog computers and wave shaping networks. DIFFERENTIATOR
If the input resistor of the inverting amplifier is replaced by a capacitor, it forms an inverting differentiator. The output of the circuit is the derivative of the input. Gain of the differentiator increases with increase in frequency, which makes the circuit unstable. This is a

drawback of the circuit. The output voltage 𝑉𝑜

can be expressed as 𝑉𝑜

= −𝑅𝐹

𝐶𝑖

𝑑𝑉𝑖.
𝑑𝑡

Differentiator functions as high pass filter. At high frequency it becomes unstable and breaks into oscillations. Input impedance decreases with increase in frequency which makes the circuit very susceptible to high frequency noise. Both stability and high frequency noise problems can be reduced significantly by additional circuit elements.

DESIGN AND CIRCUIT DIAGRAMS
<img width="288" height="272" alt="image" src="https://github.com/user-attachments/assets/244239d4-7ebb-4a9b-b2eb-2859d5c59ac0" />
<img width="329" height="210" alt="image" src="https://github.com/user-attachments/assets/573c7888-feac-4851-86b8-d52bc61689d4" />



DESIGN OF INTEGRATOR

Let the input frequency be 1 kHz. The frequency at which the integrator gives unity gain


output is given by, f = 1 / 2pi R1C
Let C = 0.01μF. then R1 = 15.9 kΩ. Use 15 kΩ std.

R2 470 kΩ







Vi
Vo



Fig. 1. Circuit diagram of Integrator	Fig. 2. Circuit diagram of Differentiator

The resistor R2 in the integrator is provided to attenuate low frequency signals, particularly input dc offset voltage that may be present. Typically, the value of R2 is selected as 10 times R1 or more. Select the value of R2 as 470 k.

DESIGN OF DIFFERENTIATOR

We have, f 
                            2 pi RC

Let C = 0.01μF. then R = 15.9 kΩ. Use 15 kΩ std.

PROCEDURE

INTEGRATOR

1.Set up the integrator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output simultaneously on CRO.
2.Vary the dc offset of the square wave input and observe the difference in the output waveform.
3.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.
DIFFERENTIATOR

1.Set up the differentiator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output

simultaneously on CRO.
2.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.


WAVEFORMS
<img width="226" height="173" alt="image" src="https://github.com/user-attachments/assets/406a6a3d-5e9e-4652-a2a9-8b05669361f3" />

Vi	Vi
Vo	Vo
Fig 3. Integrator output	Fig 4. Differentiator output
RESULT

The design and set up an integrator and differentiator circuit using op-amp has been executed successfully and the output is drawn


output voltage 𝑉𝑜

can be expressed as	𝑉𝑜

= − 1
𝑅𝐶

∫ 𝑉𝑖𝑑𝑡 + 𝑘 where k is the constant of

integration which depends upon the value of 𝑉𝑜 at t = 0. The peak of the output waveform 𝑉𝑇

is given by the expression 𝑉𝑇

=  𝑉𝑇 , where T is the time period of the input square wave.
4𝑅𝐶

Integrators are commonly used in analog computers and wave shaping networks. DIFFERENTIATOR
If the input resistor of the inverting amplifier is replaced by a capacitor, it forms an inverting differentiator. The output of the circuit is the derivative of the input. Gain of the differentiator increases with increase in frequency, which makes the circuit unstable. This is a

drawback of the circuit. The output voltage 𝑉𝑜

can be expressed as 𝑉𝑜

= −𝑅𝐹

𝐶𝑖

𝑑𝑉𝑖.
𝑑𝑡

Differentiator functions as high pass filter. At high frequency it becomes unstable and breaks into oscillations. Input impedance decreases with increase in frequency which makes the circuit very susceptible to high frequency noise. Both stability and high frequency noise problems can be reduced significantly by additional circuit elements.

DESIGN AND CIRCUIT DIAGRAMS

DESIGN OF INTEGRATOR

Let the input frequency be 1 kHz. The frequency at which the integrator gives unity gain


output is given by, f = 1 / 2pi R1C
Let C = 0.01μF. then R1 = 15.9 kΩ. Use 15 kΩ std.

R2 470 kΩ







Vi
Vo



Fig. 1. Circuit diagram of Integrator	Fig. 2. Circuit diagram of Differentiator

The resistor R2 in the integrator is provided to attenuate low frequency signals, particularly input dc offset voltage that may be present. Typically, the value of R2 is selected as 10 times R1 or more. Select the value of R2 as 470 k.

DESIGN OF DIFFERENTIATOR

We have, f 
                            2 pi RC

Let C = 0.01μF. then R = 15.9 kΩ. Use 15 kΩ std.

PROCEDURE

INTEGRATOR

1.Set up the integrator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output simultaneously on CRO.
2.Vary the dc offset of the square wave input and observe the difference in the output waveform.
3.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.
DIFFERENTIATOR

1.Set up the differentiator circuit as shown in figure. Give a rectangular wave of ±5V (10V pp) and 1 kHz frequency at the input and observe the input and output

simultaneously on CRO.
2.Repeat the experiment by feeding triangular wave and sine wave at the input and observe the output.


WAVEFORMS
Vi	Vi
Vo	Vo
Fig 3. Integrator output	Fig 4. Differentiator output
RESULT

The design and set up an integrator and differentiator circuit using op-amp has been executed successfully and the output is drawn
