Vahid Hakimi
# Microphone Sound Detection with PicoScope

## Project Overview
This project uses a microphone connected to a 9V battery and resistor, monitored with PicoScope 7.2.10 to visualize AC voltage changes when sound is detected.

## Components Used
- Electret microphone
- 9V battery
- Resistor (value depends on microphone specs, typically 2.2kΩ - 10kΩ)
- PicoScope 7.2.10
- Wires for connections

## Circuit Wiring
1. **Microphone +** → Connect to **9V battery positive** through a **resistor** (acts as a load)
2. **Microphone -** → Connect to **9V battery negative** (ground)
3. **PicoScope probe** → Connect across the microphone terminals or across the resistor to measure AC voltage output 

## How It Works
- The microphone acts as a variable resistor that changes with sound pressure
- The 9V battery provides bias voltage through the resistor
- Sound waves cause the microphone's internal diaphragm to vibrate
- This creates small AC voltage variations superimposed on the DC bias
- PicoScope captures and displays these AC voltage fluctuations

## PicoScope 7.2.10 Setup
1. Connect the probe to Channel A
2. Set coupling to **AC** (to remove DC offset and view only sound-induced changes)
3. Adjust voltage range (typically ±100mV to ±1V for microphone output)
4. Set timebase to capture sound events (e.g., 10-100 ms/div)
5. Enable triggering if needed to capture specific sound events

## Expected Results
- When silent: stable DC level (or flat line if AC coupled)
- When sound is made: AC voltage waveform appears
- Louder sounds = larger amplitude AC signal
- Different frequencies = different waveform shapes

## Troubleshooting
- **No signal**: Check battery voltage, resistor connections, and PicoScope probe connections
- **Noise / interference**: Ensure proper grounding and use shielded cables if possible
- **Distorted waveform**: Verify resistor value matches microphone specifications

## Notes
- Typical microphone output: 10mV - 100mV AC for normal speech
- Resistor value affects sensitivity: higher resistance = more sensitive but more noise
- Consider adding a capacitor in series for true AC coupling if needed
