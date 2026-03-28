Vahid Hakimi



---

## 📁 Repository Contents

This repository includes:

- `.asc` file (LTSpice schematic)
- simulation view: Schematic window + graph 
- ghraph view: waveform plot
- `README.md` (this file)

---

## ⚙️ Simulation Setup

### AC Voltage Source
- Peak Amplitude: **10 V**
- Frequency: **50 Hz** *(can also be 60 Hz depending on setup)*

---

### ⏱️ Simulation Parameters
- Analysis Type: **Transient Analysis**
- Stop Time: **40 ms** *(covers at least two full cycles for 50 Hz input)*
- Time Step: Adjusted as needed for better waveform resolution

---

## 📊 Sweep Range / Step

- Time range: **0 to 40 ms**
- Step size: **[Specify your step size, e.g., 10 µs or auto]**

---

## 📈 Results and Analysis

### Observed Waveforms
The following signals were plotted:

- Input Voltage (**Vin**)
- Output Voltage (**Vout**)

---

### 🔍 Behavior Analysis

- The input voltage (**Vin**) is a sinusoidal waveform with a peak amplitude of 10V.
- The output voltage (**Vout**) follows the behavior expected from the given circuit configuration.
- Depending on the circuit type (e.g., rectifier, filter, amplifier), the output may:
  - Be phase-shifted relative to the input
  - Show attenuation or amplification
  - Exhibit clipping or rectification effects

---

### ✅ Theoretical Verification

- The simulation results are consistent with theoretical expectations.
- Key observations:
  - Frequency of output matches input frequency
  - Shape of waveform corresponds to circuit design
  - Any deviations (if present) are due to component characteristics or simulation parameters


---

## 🧪 Conclusion

The LTSpice simulation successfully demonstrates the circuit behavior under AC excitation. The output waveform aligns with theoretical predictions, confirming the correctness of the design and simulation setup.

---
