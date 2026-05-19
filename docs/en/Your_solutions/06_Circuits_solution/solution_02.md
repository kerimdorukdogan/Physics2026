# ⚡ Problem 2 — Resistors

## 📌 Given

You have exactly three resistors:

- 🔸 R1 = 1 Ω
- 🔸 R2 = 1 Ω
- 🔸 R3 = 1 Ω

We must find all possible unique equivalent resistances using all three resistors.

---

# 🔸 Case 1 — All in Series

## 📖 Formula

R_eq = R1 + R2 + R3

---

## 🧮 Calculation

R_eq = 1 + 1 + 1

R_eq = 3 Ω

---

# ✅ Result

- 🔹 Equivalent resistance = 3 Ω

---

# 🔸 Case 2 — All in Parallel

## 📖 Formula

1 / R_eq = 1/R1 + 1/R2 + 1/R3

---

## 🧮 Calculation

1 / R_eq = 1 + 1 + 1

1 / R_eq = 3

R_eq = 1/3 Ω

R_eq ≈ 0.333 Ω

---

# ✅ Result

- 🔹 Equivalent resistance ≈ 0.333 Ω

---

# 🔸 Case 3 — Two in Series, Then Parallel with Third

## 📖 Step 1 — Series Pair

R_series = 1 + 1

R_series = 2 Ω

---

## 📖 Step 2 — Parallel Combination

R_eq = (R_series × 1) / (R_series + 1)

---

## 🧮 Calculation

R_eq = (2 × 1) / (2 + 1)

R_eq = 2 / 3 Ω

R_eq ≈ 0.667 Ω

---

# ✅ Result

- 🔹 Equivalent resistance ≈ 0.667 Ω

---

# 🔸 Case 4 — Two in Parallel, Then Series with Third

## 📖 Step 1 — Parallel Pair

R_parallel = (1 × 1) / (1 + 1)

R_parallel = 1/2 Ω

---

## 📖 Step 2 — Add Third Resistor

R_eq = 1/2 + 1

R_eq = 3/2 Ω

R_eq = 1.5 Ω

---

# ✅ Result

- 🔹 Equivalent resistance = 1.5 Ω

---

# 📊 Final Unique Values

| Configuration | Equivalent Resistance |
|---|---:|
| All Parallel | 0.333 Ω |
| Series → Parallel Combo | 0.667 Ω |
| Parallel → Series Combo | 1.5 Ω |
| All Series | 3 Ω |

---

## 🧠 Observation

- 🔸 Series connections increase resistance.
- 🔹 Parallel connections decrease resistance.
- ⚡ Mixed combinations create intermediate values.