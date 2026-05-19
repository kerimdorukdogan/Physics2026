# ⚡ Problem 5 — Kirchhoff's Laws

## 📌 Given

- 🔸 R1 = 20 Ω
- 🔸 R2 = 10 Ω
- 🔸 internal resistance = 1 Ω for each source
- 🔋 E1 = 4.5 V
- 🔋 E2 = 9 V

We need to find the currents:

- I1 through R1
- I2 through R2
- I3 through the right branch

---

# 🔸 Step 1 — Choose Node Voltage

Let the voltage between the top node and bottom node be:

V = V_top - V_bottom

Now each branch current can be written using Ohm's law.

---

# 🔸 Step 2 — Write Branch Currents

## Left branch

The left branch has R1 and internal resistance in series:

R_left = 20 + 1 = 21 Ω

I1 = (V - 4.5) / 21

---

## Middle branch

The middle branch has only R2:

I2 = V / 10

---

## Right branch

The right branch has internal resistance and source E2:

I3 = (V - 9) / 1

I3 = V - 9

---

# 🔸 Step 3 — Apply Kirchhoff's Current Law

At the top node:

I1 + I2 + I3 = 0

So:

(V - 4.5) / 21 + V / 10 + (V - 9) = 0

---

# 🔸 Step 4 — Solve for V

V ≈ 8.03 V

---

# 🔸 Step 5 — Calculate Currents

## Current I1

I1 = (8.03 - 4.5) / 21

I1 ≈ 0.168 A

---

## Current I2

I2 = 8.03 / 10

I2 ≈ 0.803 A

---

## Current I3

I3 = 8.03 - 9

I3 ≈ -0.971 A

The negative sign means the real direction of I3 is opposite to the direction we assumed.

---

# ✅ Final Answer

- 🔹 I1 ≈ 0.168 A
- 🔹 I2 ≈ 0.803 A
- 🔹 I3 ≈ -0.971 A

So the real current in the right branch has magnitude:

- 🔹 |I3| ≈ 0.971 A