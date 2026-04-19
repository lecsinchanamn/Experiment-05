# Experiment-05
# AIM
Design and analyze a non-inverting amplifier using an operational amplifier and study its frequency response.
# Parameter Table – Non-Inverting Amplifier

| Parameter | Value |
|----------|------|
| Supply Voltage (Vcc / Vee) | ±15 V |
| Input Voltage (Vin peak-to-peak) | 12 V (P-P) |
| Input Frequency (f) | 2 kHz |
| Feedback Resistor (R1) | 1 kΩ |
| Input Resistor (R2) | 4 kΩ |
| Closed-Loop Gain (Av) | 1 + (R1/R2) = 1.25 |
| Output Voltage (Vout P-P) | ≈ 15 V |
| Op-Amp Model | LM741 |

# Circuit diogram
https://github.com/lecsinchanamn/Experiment-05/blob/ffe936539d688d44c1d07fc02061999f6fbec72c/simulation%20CKT%2001.PNG

# Theory – Non-Inverting Amplifier
A Non-Inverting Amplifier uses an op-amp (LM741) where the input is applied to the + terminal and feedback is given to the − terminal.  
The voltage gain is \( A_v = 1 + \frac{R1}{R2} = 1.25 \), so the output is amplified without phase reversal.  
It provides high input impedance and low output impedance.  
It is widely used for signal amplification and conditioning.

