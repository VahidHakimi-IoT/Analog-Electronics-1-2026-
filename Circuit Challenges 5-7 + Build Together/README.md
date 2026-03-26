# Light-Controlled Transistor Circuit with Capacitor Triggering

## Name(s)

Vahid Hakimi

---

## Circuit Description

This circuit is a **light-sensitive switching circuit** built using:

* 1 × LDR (Light Dependent Resistor)
* 2 × NPN Transistors
* 1 × Capacitor
* 1 × LED
* Resistors
* 9V Battery
* Breadboard and jumper wires

The circuit combines **light sensing (LDR)** with **transistor switching**, and uses a **capacitor to influence switching behavior**.

---

## Working Principle

### 1. Light Detection (LDR)

* The LDR changes resistance based on light:

  * Bright light → low resistance
  * Darkness → high resistance

* This affects the voltage applied to the **first transistor (Q1)**.

---

### 2. Transistor Switching

* When the LDR causes enough voltage at the base:

  * Q1 turns ON
  * This influences the second transistor (Q2)
  * Q2 drives the LED

* The LED turns ON/OFF depending on light conditions.

---

### 3. Role of the Capacitor

* The capacitor is connected between transistor stages.
* When its **negative leg (short leg)** is connected toward the other transistor:

  * It briefly transfers charge to the base of the second transistor
  * This creates a **temporary switching effect**

⚡ Important:

* This does **NOT create continuous oscillation**
* It only adds a **delay or pulse effect** during switching

---

## Behavior Analysis

### Observations:

* The LED responds to changes in light intensity.
* When light conditions change:

  * The LED may briefly flicker or respond with a delay due to the capacitor.
* The circuit does **not blink continuously** on its own.

---

## Explanation

* The circuit acts mainly as a **light-controlled switch**.

* The capacitor provides:

  * A **short pulse**
  * A **smoother transition** between ON and OFF states

* Since there is only **one capacitor and no full cross-coupling**, it is **not an astable multivibrator (oscillator)**.

---

## Conclusion

* The circuit successfully detects light and controls an LED.
* The capacitor improves switching behavior by adding a **transient response**.
* This is a combination of:

  * Sensor input (LDR)
  * Amplification (transistors)
  * Temporary energy storage (capacitor)

---

## Applications

* Light-sensitive switches
* Automatic lighting systems
* Simple sensor-triggered circuits

---

## Submitted Files

* Breadboard circuit image
* README.md
