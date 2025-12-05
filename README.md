3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM

<img width="1600" height="994" alt="image" src="https://github.com/user-attachments/assets/2de043ce-7605-4b16-9019-8de49c7b274a" />



## MODEL GRAPH
<img width="1600" height="1150" alt="image" src="https://github.com/user-attachments/assets/34fd2409-74aa-45a2-98e3-0635f711231d" />

---

## DESIGN

<img width="1462" height="1600" alt="image" src="https://github.com/user-attachments/assets/943fcdf8-9404-4a23-b4fc-a522bdc3eb00" />

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION

<img width="1600" height="642" alt="image" src="https://github.com/user-attachments/assets/4b04861f-9b51-4759-b032-d0bf2696c4f8" />

		

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="1303" height="1600" alt="image" src="https://github.com/user-attachments/assets/9d3bb6e6-db9d-4de4-92bd-75dc104ff966" />


---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/7ef537bd-f5de-4f25-a5f6-eba63589d865" />


## MODEL GRAPH

<img width="1397" height="1600" alt="image" src="https://github.com/user-attachments/assets/dc9ff785-92ad-4835-b7e3-ff373c0ccdf4" />



---

## DESIGN

<img width="1462" height="1600" alt="image" src="https://github.com/user-attachments/assets/8fb22bab-3e5b-4574-b1d7-0415624af3c2" />


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION

<img width="1600" height="828" alt="image" src="https://github.com/user-attachments/assets/ade05211-fee9-4484-a202-606d58da868a" />
		

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1397" height="1600" alt="image" src="https://github.com/user-attachments/assets/6ebf9b0a-cbe6-46aa-ab32-a64f1cb5ec3b" />

---

RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---



