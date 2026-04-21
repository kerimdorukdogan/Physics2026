# 🧲 Section 2: Mechanics II  
## 💥 4. Energy & Momentum

---

## 📌 Problem

> A **0.5 kg** block slides down a frictionless track from a height of **3.0 m**.  
> At the bottom, it collides and sticks to a **1.5 kg** block (initially at rest).  
>
> What is the **final speed** of the combined mass just after the collision?

---

<details>
<summary>📖 🔎 Click to see theory</summary>

### Step 1 — Energy Conservation (before collision)

$$
mgh = \frac{1}{2}mv^2
$$

$$
v = \sqrt{2gh}
$$

---

### Step 2 — Momentum Conservation (during collision)

In an inelastic collision:

$$
m_1 v_1 + m_2 v_2 = (m_1 + m_2)v_f
$$

Since second block is at rest:

$$
m_1 v_1 = (m_1 + m_2)v_f
$$

</details>

---

## 🚀 Step 1 — Speed before collision

Use:

$$
v = \sqrt{2gh}
$$

Substitute:

$$
v = \sqrt{2 \cdot 9.81 \cdot 3}
$$

$$
v = \sqrt{58.86}
$$

$$
v \approx 7.67\ \text{m/s}
$$

---

## 🚀 Step 2 — Apply momentum conservation

Given:

- $m_1 = 0.5\ \text{kg}$
- $m_2 = 1.5\ \text{kg}$
- $v_1 = 7.67\ \text{m/s}$
- $v_2 = 0$

Use:

$$
m_1 v_1 = (m_1 + m_2)v_f
$$

Substitute:

$$
0.5 \cdot 7.67 = (0.5 + 1.5)v_f
$$

$$
3.835 = 2v_f
$$

$$
v_f = \frac{3.835}{2}
$$

$$
v_f \approx 1.92\ \text{m/s}
$$

---

## ✅ Final Answer

$$
\boxed{v_f \approx 1.92\ \text{m/s}}
$$

---

## 📊 Quick Summary

| Quantity | Value |
|----------|------|
| Initial height | $3.0\ \text{m}$ |
| Speed before collision | $7.67\ \text{m/s}$ |
| Total mass after collision | $2.0\ \text{kg}$ |
| Final speed | $1.92\ \text{m/s}$ |

---

## 🧠 Physical Insight

- First: potential energy → kinetic energy  
- Then: collision happens  
- Momentum is conserved  
- Energy is **NOT conserved** (because they stick)

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Height 3m] --> B[Convert to speed]
    B --> C[v ≈ 7.67 m/s]
    C --> D[Collision]
    D --> E[Objects stick]
    E --> F[Momentum conserved]
    F --> G[v_final ≈ 1.92 m/s]