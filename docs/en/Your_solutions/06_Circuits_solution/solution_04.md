# ⚡ Problem 4 — Mixed Circuit

## 📌 Given

All resistors have:

- 🔸 R = 10 Ω

We must calculate the equivalent resistance between the two terminals.

---

# 🔸 Step 1 — Top Branch

The top branch contains two resistors in series.

## 🧮 Calculation

R_top = 10 + 10

R_top = 20 Ω

---

# 🔸 Step 2 — Bottom Small Parallel Part

At the bottom, there are two resistors connected between the same two points.

Because of this, they are connected in parallel.

## 📖 Formula

1 / R_parallel = 1/10 + 1/10

---

## 🧮 Calculation

1 / R_parallel = 2/10

1 / R_parallel = 1/5

R_parallel = 5 Ω

---

# 🔸 Step 3 — Bottom Branch

Now we combine the left bottom resistor with the parallel result.

These are connected in series.

## 🧮 Calculation

R_bottom = 10 + 5

R_bottom = 15 Ω

---

# 🔸 Step 4 — Main Parallel Combination

Now the top branch and bottom branch are connected in parallel.

## 📖 Formula

1 / R_main = 1/20 + 1/15

---

## 🧮 Calculation

Common denominator is 60:

1 / R_main = 3/60 + 4/60

1 / R_main = 7/60

R_main = 60/7

R_main ≈ 8.57 Ω

---

# 🔸 Step 5 — Final Series Resistor

At the right side, there is one more resistor in series.

## 🧮 Calculation

R_total = 8.57 + 10

R_total ≈ 18.57 Ω

---

# ✅ Final Answer

- 🔹 Equivalent resistance ≈ 18.57 Ω