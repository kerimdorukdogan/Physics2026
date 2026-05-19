# ⚡ Problem 6 — Kirchhoff's Laws Again

## 📌 Given

- 🔋 E1 = 9 V
- 🔋 E2 = 4.5 V
- 🔸 R1 = 10 Ω
- 🔸 R2 = 20 Ω
- 🔸 Internal resistance = 1 Ω for each battery

We need to find the current flowing through the ammeter.

---

# 🔸 Step 1 — Define Nodes

Let the left node be:

V_left = 0 V

Let the upper-right node be:

V_B

Let the lower-right node be:

V_C

---

# 🔸 Step 2 — Write Kirchhoff Equations

Using Kirchhoff's current law at node B:

(V_B + 4.5) / 1 + V_B / 20 + (V_B - V_C) / 10 = 0

Using Kirchhoff's current law at node C:

(V_C + 9) / 1 + (V_C - V_B) / 10 = 0

---

# 🔸 Step 3 — Solve the Equations

After solving:

V_B ≈ -4.66 V

V_C ≈ -8.61 V

---

# 🔸 Step 4 — Current Through Ammeter

The ammeter is in series with R2.

So the ammeter current is the same as the current through R2.

I_A = (V_left - V_B) / R2

I_A = (0 - (-4.66)) / 20

I_A = 4.66 / 20

I_A ≈ 0.233 A

---

# ✅ Final Answer

- 🔹 Current through the ammeter ≈ 0.233 A

The current flows from the left side toward the right side through R2.