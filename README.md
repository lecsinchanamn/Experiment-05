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
# DC Analysis
.   When Vin = 0 V: Vout ≈ 0 V  
.   This indicates the op-amp is properly biased in the non-inverting configuration.  
.   small offset voltage may appear due to practical limitations of the LM741.  
.   The output remains stable within the ±15 V supply range under DC conditions.

https://github.com/lecsinchanamn/Experiment-05/blob/80df08e30998bb19e336ba3f1b2abd55f76be81d/Ckt%2002%20DC%20analysis.PNG

# Tranisnt Analysis
.  Input waveform (Vin) is a sinusoidal signal at 2 kHz.  
.  Output waveform (Vout) is amplified by a gain of 1.25 and remains in phase with the input.  
.  Output may show slight clipping near ±15 V due to LM741 practical limitations.

 https://github.com/lecsinchanamn/Experiment-05/blob/4a8075e8af8dac0a14563b9d59831e91f25cf823/Ckt%2003%20TA.PNG

#  AC Analysis or Frequeny response
https://github.com/lecsinchanamn/Experiment-05/blob/d5233cd011fd7c9b4e20e293c630d13d13b5b86e/Ckt%2004%20AC%20analysis.PNG
