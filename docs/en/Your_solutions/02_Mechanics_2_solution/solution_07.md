# 🧱 7. Dynamics with Friction

---

## 📌 Problem

A **5 kg block** is placed on a **10 kg block**.  
A horizontal force of **45 N** is applied to the **10 kg block**, and the **5 kg block is tied to the wall**.  
The coefficient of **kinetic friction** between all moving surfaces is **0.2**.

👉 Find the **acceleration of the 10 kg block**.

---

<details>
<summary>📖 🔎 Click to see theory</summary>

### Main idea

The **10 kg block** moves to the right, but two friction forces oppose its motion:

1. **Friction with the upper 5 kg block**
2. **Friction with the ground**

So:

$$
F_{\text{net}} = F - f_{\text{top}} - f_{\text{ground}}
$$

And then:

$$
a = \frac{F_{\text{net}}}{m}
$$

</details>

---

## 🚀 Step 1 — Friction from the top block

Since the **5 kg block is tied to the wall**, the **10 kg block slides under it**.

So kinetic friction acts between the two blocks:

$$
f_{\text{top}} = \mu_k N_{\text{top}}
$$

The normal force from the top block is:

$$
N_{\text{top}} = m_{\text{top}} g = 5 \cdot 9.81 = 49.05\ \text{N}
$$

So:

$$
f_{\text{top}} = 0.2 \cdot 49.05 = 9.81\ \text{N}
$$

---

## 🚀 Step 2 — Friction with the ground

The ground supports both blocks, so:

$$
N_{\text{ground}} = (5 + 10)g = 15 \cdot 9.81 = 147.15\ \text{N}
$$

Thus the kinetic friction with the ground is:

$$
f_{\text{ground}} = \mu_k N_{\text{ground}}
$$

$$
f_{\text{ground}} = 0.2 \cdot 147.15 = 29.43\ \text{N}
$$

---

## 🚀 Step 3 — Net force on the 10 kg block

Applied force:

$$
F = 45\ \text{N}
$$

Opposing friction forces:

$$
f_{\text{top}} = 9.81\ \text{N}
$$

$$
f_{\text{ground}} = 29.43\ \text{N}
$$

So the net force is:

$$
F_{\text{net}} = 45 - 9.81 - 29.43
$$

$$
F_{\text{net}} = 5.76\ \text{N}
$$

---

## 🚀 Step 4 — Acceleration

The moving block has mass:

$$
m = 10\ \text{kg}
$$

Using Newton's second law:

$$
a = \frac{F_{\text{net}}}{m}
$$

$$
a = \frac{5.76}{10}
$$

$$
a = 0.576\ \text{m/s}^2
$$

---

## ✅ Final Answer

$$
\boxed{a \approx 0.58\ \text{m/s}^2}
$$

---

## 🔍 Why does this happen?

- The **10 kg block** is pulled to the right
- The **5 kg block cannot move** because it is tied to the wall
- So the lower block slides under the upper one
- Friction appears at both contacts:
  - between the two blocks
  - between the lower block and the ground

Both friction forces reduce the acceleration.

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Apply 45 N to 10 kg block] --> B[Friction from top block]
    A --> C[Friction from ground]
    B --> D[Reduce net force]
    C --> D
    D --> E[Use Fnet = ma]
    E --> F[a ≈ 0.58 m/s²]