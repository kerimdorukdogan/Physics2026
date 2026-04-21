# 🧲 Section 2: Mechanics II  
## 🌍 1. Gravitational Dependence

---

## 📌 Problem

> A simple pendulum has a period of **4 seconds on Earth**.  
> What would its period be on the **Moon**, where gravity is **1/6 of Earth's**?  
>
> What is the required **length** of a pendulum to have a period of **1 second on Earth**?

---

<details>
<summary>📖 🔎 Click to see theory</summary>

### Pendulum Formula

$$
T = 2\pi \sqrt{\frac{l}{g}}
$$

- $T$ → Period  
- $l$ → Length  
- $g$ → Gravity  

👉 Key idea:

$$
T \propto \frac{1}{\sqrt{g}}
$$

</details>

---

## 🚀 Part A — Period on the Moon

### Given

- $T_E = 4\ \text{s}$
- $g_M = \frac{g_E}{6}$

---

### Solution

$$
\frac{T_M}{T_E} = \sqrt{\frac{g_E}{g_M}}
$$

$$
\frac{T_M}{4} = \sqrt{6}
$$

$$
T_M = 4\sqrt{6}
$$

$$
T_M \approx 4 \cdot 2.45 = 9.8\ \text{s}
$$

---

### ✅ Final Answer

$$
\boxed{T_M \approx 9.8\ \text{s}}
$$

---

## 🚀 Part B — Length for 1-second Pendulum

### Start from:

$$
T = 2\pi \sqrt{\frac{l}{g}}
$$

---

### Solve for $l$

$$
l = g\left(\frac{T}{2\pi}\right)^2
$$

---

### Substitute

$$
l = 9.81 \left(\frac{1}{2\pi}\right)^2
$$

$$
l = \frac{9.81}{4\pi^2}
$$

$$
l \approx \frac{9.81}{39.48}
$$

$$
l \approx 0.248\ \text{m}
$$

---

### ✅ Final Answer

$$
\boxed{l \approx 0.25\ \text{m} \ (25\ \text{cm})}
$$

---

## 📊 Quick Comparison

| Parameter | Earth 🌍 | Moon 🌙 |
|----------|--------|--------|
| Gravity | $g$ | $g/6$ |
| Effect | Faster motion | Slower motion |
| Period | 4 s | 9.8 s |

---

## 🧠 Physical Insight

- Lower gravity → weaker restoring force  
- Pendulum moves slower  
- Period increases  

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Pendulum Formula] --> B[Same Length]
    B --> C[Earth: High g]
    B --> D[Moon: Low g]
    C --> E[Shorter Period]
    D --> F[Longer Period]