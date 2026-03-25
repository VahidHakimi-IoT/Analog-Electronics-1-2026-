Vahid Hakimi

Sweep Range / Step dioide application assignment

No parameter sweep was used in this simulation.
The transient analysis was performed over a time range of 0 to 40 ms with a fixed maximum time step of 0.1 ms to ensure waveform clarity.

Circuit Description

A full-wave bridge rectifier was built using:

4 diodes
AC voltage source (100 V peak)
Load resistor

In the second part of the simulation:

A capacitor was added across the load to smooth the output voltage.
Results & Analysis
1. Without Capacitor
The output voltage (Vout) is a full-wave rectified signal.
Both positive and negative halves of the AC input are converted into positive voltage.
The waveform is pulsating DC, not smooth.
Frequency of output ripple is twice the input frequency (100 Hz).

Observation:
The voltage drops to zero between peaks, meaning it is not suitable for most DC applications.

2. With Capacitor
Adding a capacitor across the load smooths the output voltage.
The capacitor charges to the peak voltage and discharges slowly when the input drops.
This reduces fluctuations (ripple) in the output.

Observation:

The output becomes closer to DC.
Small ripples remain due to capacitor discharge.
Larger capacitance → smoother output (less ripple).
Conclusion
The full-wave rectifier successfully converts AC to DC.
Without filtering, the output is pulsating and unstable.
Adding a capacitor significantly improves the output by smoothing the voltage.
This demonstrates the practical importance of filtering in power supply circuits.
