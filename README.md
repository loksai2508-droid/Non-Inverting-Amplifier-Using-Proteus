## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V

<img width="718" height="398" alt="image" src="https://github.com/user-attachments/assets/518fb3d6-fca6-416d-b61a-a982af265aef" />

## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform

<img width="722" height="443" alt="image" src="https://github.com/user-attachments/assets/185a2604-42e7-4175-8490-6b0c174ecfc7" />

## Tabulation
S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)

| Sl. No | Input Voltage (Vin) | Output Voltage (Vout = 11Vin) |
| ------ | ------------------- | ----------------------------- |
| 1      | +0.1 V              | +1.1 V                        |
| 2      | +0.2 V              | +2.2 V                        |
| 3      | +0.5 V              | +5.5 V                        |
| 4      | 0 V                 | 0 V                           |
| 5      | –0.1 V              | –1.1 V                        |
| 6      | –0.2 V              | –2.2 V                        |
| 7      | –0.5 V              | –5.5 V                        |

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?

   Non-Inverting Amplifier: An op-amp circuit where the input is applied to the (+) terminal and the output is amplified without phase inversion.

2.	What is the gain formula?
 
   Av​=1+R1​Rf​​
3.	Why is output in phase?

Why Output is In Phase: Because the input is applied to the non-inverting (+) terminal, so there is no phase reversal (0° shift).

4.	What happens if Rf increases?

 Increases: The voltage gain increases.

5.	What is the input impedance of non-inverting amplifier?

   Input Impedance: Very high (ideally infinite).

