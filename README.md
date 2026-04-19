# Experiment-05
# CIRCUIT 01
# AIM
Design and analyze a non-inverting amplifier using an operational amplifier and study its frequency response.
# Circuit diogram
https://github.com/lecsinchanamn/Experiment-05/blob/ffe936539d688d44c1d07fc02061999f6fbec72c/simulation%20CKT%2001.PNG

# Theory – Non-Inverting Amplifier
A Non-Inverting Amplifier uses an op-amp (LM741) where the input is applied to the + terminal and feedback is given to the − terminal.  
The voltage gain is \( A_v = 1 + \frac{R1}{R2} = 1.25 \), so the output is amplified without phase reversal.  
It provides high input impedance and low output impedance.  
It is widely used for signal amplification and conditioning.

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

#  AC Analysis or Frequency response. 
.  Observation: Gain ≈ 1.94 dB (for Av = 1.25)  
.  Gain remains constant at low and mid frequencies.  
.  Gain decreases at higher frequencies.
.  Reason: Due to internal capacitances and finite gain-bandwidth product of the LM741 op-amp.

https://github.com/lecsinchanamn/Experiment-05/blob/cdc6a93a5e3041f17ae6b71275fb85b0ee5b7a46/Ckt%2004%20AC%20analysis.PNG

# Frequency response and bandwidth characteristics.
. Observation: Gain ≈ 1.94 dB (Av = 1.25).  
. Gain is almost constant at low frequencies.  
. At high frequencies, the gain starts decreasing.
. Reason: This happens due to internal capacitances and limited bandwidth of the op-amp.

https://github.com/lecsinchanamn/Experiment-05/blob/24731fe652af8c77875471b3681acc6cf2af4ad1/Ckt%2005%20AC%20analysis.PNG

# Conclusion & Interpretation
.  The circuit works as a non-inverting amplifier with a gain of about 1.25, amplifying the input without changing its phase.  
.  The output follows the input signal shape and stays stable within the supply limits.  
.  At higher frequencies, the gain reduces due to op-amp limitations.  
.  Overall, the circuit performs as expected for basic signal amplification.

# CIRCUIT 02
# AIM
Design and analyze a voltage follower (unity gain buffer) and study the frequency response.
# Circuit diogram
https://github.com/lecsinchanamn/Experiment-05/blob/e9643c7490e743511ff4c07697cdaaaf94986c22/ckt2.%2001.PNG
# Theory of voltage follower circuit
. This circuit is a Voltage Follower using an LM741 op-amp, where the output is directly fed back to the inverting (−) terminal.  
. The input signal is applied to the non-inverting (+) terminal, so the output follows the input.  
. The voltage gain of this circuit is unity.
. Av = Vout / Vin = 1  
. This means the output voltage is equal to the input voltage (Vout = Vin), with no phase change.  
It provides very high input impedance and low output impedance, making it useful as a buffer.


# Parameter Table – Voltage Follower (Buffer)

| Parameter | Value |
|----------|------|
| Supply Voltage (Vcc / Vee) | ±15 V |
| Input Voltage (Vin peak-to-peak) | 12 V (P-P) |
| Input Frequency (f) | 2 kHz |
| Load Resistor (R1) | 2.2 kΩ |
| Closed-Loop Gain (Av) | Av = Vout / Vin = 1 |
| Output Voltage (Vout P-P) | ≈ 12 V (P-P) |
| Op-Amp Model | LM741 |

# DC Analysis 
.  When Vin = 0 V: Vout ≈ 0 V  
.  The output follows the input due to unity feedback (voltage follower action).  
.  The op-amp is properly biased with ±15 V supply.  
.  A small offset voltage may appear due to practical limitations of the LM741.

https://github.com/lecsinchanamn/Experiment-05/blob/233dbdf434ea958efa37b7673495ecb821635e79/Ckt02.%20DC%20Analysis.PNG

# Transint Analysis
.  Input waveform (Vin) is a sinusoidal signal at 2 kHz.  
.  Output waveform (Vout) closely follows the input (unity gain, no phase shift).  
.  No amplification occurs; output amplitude ≈ input amplitude (12 V P-P).  
.  Minor distortion may appear at peaks due to LM741 slew rate limitations.

https://github.com/lecsinchanamn/Experiment-05/blob/8b48661ad020aca78b717e497fb4058ca666e5a7/CKT02.%20TA%20analysis.PNG

# AC Analysis or Frequency Response
.  Gain ≈ 0 dB (Av = 1).  
.  Gain remains constant at low and mid frequencies.  
.  At higher frequencies, the gain starts to decrease.  
.  This is due to the limited bandwidth (gain-bandwidth product) of the LM741 op-amp.

https://github.com/lecsinchanamn/Experiment-05/blob/5d0a24135a6dd8e037f793fcdd821a213b6d4713/CKT02.AC%20analysis.PNG

# Frequency response and bandwidth characteristics.
- Gain (Linear): 1  
- Gain (dB): 0 dB  
- Phase Shift: 0°  
- Bandwidth: High (limited by LM741 gain-bandwidth product)
  
https://github.com/lecsinchanamn/Experiment-05/blob/a5592d4bc472037a82164502405b051cc097c949/CKT02.%20AC%20and%20FR%20analysis.PNG

# 
