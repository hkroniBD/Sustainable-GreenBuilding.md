# ⚡ **Lecture: Electrical Circuit Analysis — Laws, Theorems & Methods**

# 🧭 **1. Fundamental Laws**

These laws are the backbone of all circuit behavior.

## 🔹 **Ohm’s Law**

`V = I × R`
Defines the basic relation between voltage, current, and resistance.
**Use:** Cable sizing, LED driver circuits.

## 🔹 **Kirchhoff’s Current Law (KCL)**

Sum of currents entering a node equals sum leaving it.
**Use:** DB (distribution board) branch load calculations.

## 🔹 **Kirchhoff’s Voltage Law (KVL)**

Sum of voltages around a closed loop equals zero.
**Use:** Voltage drop in a lighting ring circuit.

---

# 🧩 **2. Circuit Analysis Methods (Brief Statements)**

## ⚙️ **Nodal Analysis**

Uses KCL to solve for node voltages.
**Use:** Complex panelboard and building wiring networks.

## ⚙️ **Mesh Analysis**

Uses KVL to determine loop currents.
**Use:** DC loops, UPS output circuits.

## ⚙️ **Superposition Method**

Analyzes circuits with multiple sources by activating one at a time.
**Use:** Buildings with grid + solar + generator.

## ⚙️ **Source Transformation**

Converts between equivalent voltage and current sources.
**Use:** Simplifying EV charger circuits or driver circuits.

---

# 🧠 **3. Network Theorems (Brief Statements)**

## 🔸 **Thevenin’s Theorem**

Any network can be reduced to a single voltage source + resistance.
**Use:** Short-circuit current estimation at sockets.

## 🔸 **Norton’s Theorem**

Equivalent of Thevenin but in current-source form.
**Use:** Solar panel modeling, current-limited supplies.

## 🔸 **Superposition Theorem**

Same as method but applied as a theorem.
**Use:** Smart building multi-source power flow.

## 🔸 **Maximum Power Transfer Theorem**

Power delivered to a load is maximum when load resistance equals source internal resistance.
**Use:** MPPT in solar inverters, audio systems.

---

# 🔄 **4. Reactive Components and Their Behavior**

## 🔹 **Capacitors**

Store electric charge; block DC; shift AC phase.
**Use:** Power factor correction, filtering.

## 🔹 **Inductors**

Store magnetic energy; oppose sudden current change.
**Use:** Motor behavior, elevator and HVAC systems.

---

# 🔸 **5. AC Analysis Concepts**

## 🔹 **Impedance (Z)**

`Z = R + X` (resistance + reactance)
**Use:** Cable sizing in tall buildings.

## 🔹 **Power Factor (PF)**

Indicates efficiency of power usage.
**Use:** Utility penalties and industrial load design.

## 🔹 **RMS Value**

Effective magnitude of AC.
**Use:** Breaker and fuse ratings.

---

# 🔺 **6. Three-Phase Circuit Concepts**

## 🔹 Star–Delta Relations

Determine line vs phase quantities.
**Use:** Connecting motors, HVAC compressors.

## 🔹 Three-Phase Power

`P = 1.732 × V × I × PF`
**Use:** Elevator, chiller, and large equipment design.

---

# 💥 **7. Transient Analysis Concepts**

## 🔹 RL/RC/RLC transient response

Describes sudden voltage/current changes.
**Use:** Surge protection, motor startup spikes.

---

# 🧱 **Summary Table (Compact Overview)**

| Item             | Brief Statement           | Key Application        |
| ---------------- | ------------------------- | ---------------------- |
| Ohm’s Law        | Relation of V, I, R       | Cable sizing           |
| KCL              | Current balance at nodes  | DB branching           |
| KVL              | Voltage balance in loops  | Voltage drop           |
| Nodal Analysis   | Solve using node voltages | Panels, risers         |
| Mesh Analysis    | Solve loop currents       | DC networks            |
| Superposition    | Multi-source circuits     | Grid + UPS             |
| Source Transform | Convert V↔I sources       | Circuit simplification |
| Thevenin         | Reduce to V-source + R    | Fault analysis         |
| Norton           | Reduce to I-source + R    | Solar PV modeling      |
| Max Power        | Load matching rule        | MPPT                   |
| Impedance        | AC opposition             | Cable & motor circuits |
| Three-phase      | 400 V systems             | HVAC, lifts            |
| Transients       | Switching behavior        | Surge, breakers        |

---

# 🧪 **Numerical Example**

A building elevator has a **15 kW** motor operating from **400 V**, **three-phase**, **PF = 0.85**.

Current needed:
`I = 15000 / (1.732 × 400 × 0.85)`
`I ≈ 25.5 A`

This guides:

* Cable size
* Breaker rating
* Contactor selection
* Thermal overload relay setting

---

# ❓ **Follow-Up Quiz**

1. Which method is best for solving many-node building distribution circuits?
2. Why is Thevenin’s theorem useful in short-circuit studies?
3. Calculate current for a 2 kW heater on 230 V supply.
4. What does power factor physically represent?

---

# ✅ **Solutions**

1. Nodal analysis.
2. Because it simplifies a large network into a single equivalent source + resistance, making fault current easy to compute.
3. `I = 2000 / 230 ≈ 8.70 A`
4. It represents how effectively electrical power is converted into useful work without phase loss.

---
