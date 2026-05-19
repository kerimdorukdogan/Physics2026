# ⚡ Problem 3 — Mixed Circuit

## 📌 Given

All resistors have:

- 🔸 R = 5 Ω

We must calculate the equivalent resistance between the two bottom terminals.

---

# 🔸 Step 1 — Left Branch

The left side contains:

- one vertical resistor
- one top horizontal resistor

These two are connected in series.

## 🧮 Calculation

R_left = 5 + 5

R_left = 10 Ω

---

# 🔸 Step 2 — Middle Branch

The middle branch contains two vertical resistors in series.

## 🧮 Calculation

R_middle = 5 + 5

R_middle = 10 Ω

---

# 🔸 Step 3 — Right Branch

The right branch also contains two vertical resistors in series.

## 🧮 Calculation

R_right = 5 + 5

R_right = 10 Ω

---

# 🔸 Step 4 — Parallel Combination

Now the middle branch and right branch are connected in parallel.

## 📖 Formula

1 / R_parallel = 1/R_middle + 1/R_right

---

## 🧮 Calculation

1 / R_parallel = 1/10 + 1/10

1 / R_parallel = 2/10

1 / R_parallel = 1/5

R_parallel = 5 Ω

---

# 🔸 Step 5 — Add Remaining Resistor

At the bottom there is one more resistor in series with the whole circuit.

## 🧮 Calculation

R_total = 5 + 5

R_total = 10 Ω

---

# ✅ Final Answer

- 🔹 Equivalent resistance = 10 Ω