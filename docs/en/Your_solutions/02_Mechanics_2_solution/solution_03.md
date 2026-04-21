# 🧲 Section 2: Mechanics II  
## ⚡ 3. Conservation of Energy

---

## 📌 Problem

> A pendulum with a length of **1.0 meter** is released from an initial angle of **15°**.  
>
> What is the **speed of the pendulum bob at the bottom** of its swing?

---

<details>
<summary>📖 🔎 Click to see theory</summary>

### Energy Conservation

Mechanical energy is conserved:

$$
E_{initial} = E_{final}
$$

At the top:
- Potential energy is maximum
- Kinetic energy is zero

At the bottom:
- Potential energy is minimum
- Kinetic energy is maximum

So:

$$
mgh = \frac{1}{2}mv^2
$$

Mass cancels:

$$
gh = \frac{1}{2}v^2
$$

$$
v = \sqrt{2gh}
$$

</details>

---

## 🚀 Step 1 — Find height difference $h$

The vertical height from angle $\theta$ is:

$$
h = l(1 - \cos\theta)
$$

Given:

- $l = 1.0\ \text{m}$
- $\theta = 15^\circ$

So:

$$
h = 1(1 - \cos 15^\circ)
$$

$$
\cos 15^\circ \approx 0.966
$$

$$
h = 1(1 - 0.966)
$$

$$
h \approx 0.034\ \text{m}
$$

---

## 🚀 Step 2 — Find velocity

Use:

$$
v = \sqrt{2gh}
$$

Substitute:

$$
v = \sqrt{2 \cdot 9.81 \cdot 0.034}
$$

$$
v = \sqrt{0.667}
$$

$$
v \approx 0.82\ \text{m/s}
$$

---

## ✅ Final Answer

$$
\boxed{v \approx 0.82\ \text{m/s}}
$$

---

## 📊 Quick Summary

| Quantity | Value |
|----------|------|
| Length | $1.0\ \text{m}$ |
| Angle | $15^\circ$ |
| Height difference | $0.034\ \text{m}$ |
| Final speed | $0.82\ \text{m/s}$ |

---

## 🧠 Physical Insight

- Energy converts from **potential → kinetic**
- At the bottom, all energy becomes **motion**
- Small angle → small height → small speed

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Start at 15°] --> B[Has potential energy]
    B --> C[Moves down]
    C --> D[Potential → Kinetic]
    D --> E[Bottom point]
    E --> F[v ≈ 0.82 m/s]