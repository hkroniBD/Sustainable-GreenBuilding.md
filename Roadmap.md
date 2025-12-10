## ⚡ Roadmap for Learning Electrical Domain Knowledge

The flow moves from **basic physics → circuit behavior → building systems → power distribution → safety → advanced applications**.
Each stage includes physical significance, real-world meaning, and simple quantitative anchors.

---

## 🧩 1. Foundation: Electricity & Basic Physics

This stage develops intuition.

### Key Concepts

* Charge, current, voltage, resistance
* Energy and power
* DC vs AC
* Frequency, phase, sinusoidal signals

### Physical Significance

Current is the *flow of charge*; voltage is the *energy per charge*.
Think of voltage as the “pressure” that pushes electrons through a conductor.

### Anchor Formula

`Power (W) = Voltage (V) × Current (A)`

### Practical Example

A 60 W LED panel on a 230 V supply draws:
`I = 60 / 230 ≈ 0.26 A`

---

## 🔌 2. Basic Electrical Circuits

This is the grammar of electrical engineering.

### What to Learn

* Series and parallel circuits
* Kirchhoff’s laws
* Ohm’s law
* Impedance (combined resistance + reactance)
* Power factor

### Physical Significance

Impedance determines how AC current “struggles” through a circuit, shaping voltage drops.

### Example

For an appliance rated at 500 W with a power factor of 0.8:
`Apparent Power = 500 / 0.8 = 625 VA`
Circuits must be sized according to **625 VA**, not just 500 W.

---

## 🏛️ 3. Building Electrical Components

Understand what actually lives inside walls and ceilings.

### Key Topics

* Switches, sockets, conduits
* Cables, insulation types
* Circuit breakers (MCB), RCCB, RCBO
* Distribution boards (DBs)
* Earthing/grounding systems

### Physical Significance

Earthing provides a low-resistance escape path so fault current does not travel through a human body.

---

## 💡 4. Lighting Systems

Lighting connects architecture and electrical engineering.

### Learn

* Lumen, lux, efficacy
* Lighting calculations
* Control systems (dimmers, sensors)
* Emergency lighting circuits

### Example

For a 300 m² reading hall requiring 500 lux:
`Required lumens = 500 × 300 = 150000 lm`
If each fixture provides 4000 lm → 37–38 fixtures.

---

## 🌬️ 5. Building Electrical Loads (HVAC, lifts, motors)

Large buildings are defined by their big loads.

### Learn

* Motor behavior
* Starting current
* HVAC electrical demands
* Load estimation
* Diversity factors

### Physical Significance

Motors draw 3–7 times their running current at startup.
This is why codes require oversized breakers and cables.

---

## 🧠 6. Power System Basics

This bridges building installations with the national grid.

### Understand

* Single-phase vs three-phase systems
* Transformers
* Distribution network structure
* Short-circuit current
* Harmonics

### Example

Three-phase power calculation:
`Power (W) = √3 × V × I × PF`

For a 10 kW motor at PF = 0.9 on 400 V:
`I ≈ 10,000 / (1.732 × 400 × 0.9) ≈ 16 A`

---

## 🔐 7. Safety, Codes, and Standards (Mandatory)

Safety is not optional—it is regulation.

### Learn

* NEC, IEC 60364, BS 7671
* Cable derating factors
* Earthing resistance limits
* Fault protection
* Inspection & testing requirements

### Example

If ambient temperature rises above 40°C, codes require derating of cable current capacity to prevent overheating.

---

## 🔆 8. Energy Efficiency & Smart Systems

For modern buildings and green architecture.

### Learn

* Solar PV basics
* Inverters
* Smart meters
* IoT-based control
* Energy management systems
* EV charging standards

### Example

Solar output estimation:
`Energy (Wh/day) ≈ Panel wattage × 4–5 sun-hours`

A 3 kW rooftop system generates ≈ 12–15 kWh/day.

---

## 📟 9. Integration & Design Practice

Applying everything in real buildings.

### Tasks

* Drafting electrical plans
* SLD (single-line diagram) preparation
* Load schedules
* Panel board layouts
* Voltage drop analysis
* Cable sizing exercises

### Example

A 50 m cable run with a 20 A load must be sized to ensure voltage drop < 3%.
Standards provide the allowable resistance per meter for calculation.

---

## 📚 Summary Table

| Stage | Focus               | Skill Gained                   |
| ----- | ------------------- | ------------------------------ |
| 1     | Basic physics       | Intuition for electricity      |
| 2     | Circuit theory      | Analytical ability             |
| 3     | Building components | Knowledge of what’s installed  |
| 4     | Lighting            | Architectural integration      |
| 5     | HVAC & loads        | Handling large demands         |
| 6     | Power systems       | Grid-building interface        |
| 7     | Codes & safety      | Compliance and protection      |
| 8     | Energy efficiency   | Modern sustainable design      |
| 9     | Design practice     | Ability to design real systems |

---

## 🧠 Follow-Up Quiz

1. What is the physical difference between resistance and impedance?
2. Why do cables need derating in high-temperature environments?
3. Calculate current for a 3000 W heater at 230 V.
4. Why does a three-phase motor require less current than an equivalent single-phase motor?

---

## 🎯 Solutions

1. Resistance opposes DC current; impedance opposes AC current and includes both resistance and reactance.
2. High temperature reduces a cable’s ability to dissipate heat, increasing the risk of insulation damage and fire.
3. `I = 3000 / 230 ≈ 13.04 A`
4. Three-phase systems deliver power more smoothly, reducing current demand for the same power output and improving efficiency.

---

A roadmap like this helps an engineer or architect grow confidently from “voltage and current” to “smart buildings and power networks,” with every stage resting on the strength of the previous one.
