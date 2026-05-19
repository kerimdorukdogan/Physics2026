# ⚡ Problem 14 — RLC Circuit

## 📌 Given

A series RLC circuit contains:

- 🔋 Voltage source: V(t)
- 🔸 Resistor: R
- 🌀 Inductor: L
- 🔹 Capacitor: C

Current is:

I(t)

Capacitor voltage is:

Vc(t)

---

# 🔸 Step 1 — Kirchhoff Voltage Law

For a series RLC circuit:

V(t) = VR + VL + VC

---

# 🔸 Step 2 — Write Each Voltage

Resistor:

VR = R × I

Inductor:

VL = L × dI/dt

Capacitor:

VC = Vc

Also:

I = C × dVc/dt

---

# 🔸 Step 3 — Substitute into the Equation

V(t) = R × C × dVc/dt + L × C × d²Vc/dt² + Vc

Rearranged:

LC × d²Vc/dt² + RC × dVc/dt + Vc = V(t)

---

# 🔸 Step 4 — Compare with Damped Harmonic Oscillator

Damped oscillator equation:

m × d²x/dt² + b × dx/dt + kx = F(t)

RLC circuit equation:

LC × d²Vc/dt² + RC × dVc/dt + Vc = V(t)

---

# 🔸 Analogy

- 🔹 LC term is like mass m
- 🔹 RC term is like damping b
- 🔹 Vc term is like spring force kx
- 🔹 V(t) is like external force F(t)

---

# ✅ Final Answer

The differential equation is:

LC × d²Vc/dt² + RC × dVc/dt + Vc = V(t)

The series RLC circuit behaves like a damped harmonic oscillator.