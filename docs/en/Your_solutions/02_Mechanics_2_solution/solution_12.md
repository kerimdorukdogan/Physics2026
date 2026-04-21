# 💪 12. Work and Energy with a Constant Force

---

## 📌 Problem

A constant force acts on a body of mass

$$
m = 2\ \text{kg}
$$

The force is:

$$
\vec F = (6,\ 2)\ \text{N}
$$

Initial conditions:

$$
\vec v(0) = (1,\ -1)\ \text{m/s}
$$

$$
\vec r(0) = (0,\ 0)\ \text{m}
$$

Find:

- $\vec a(t)$
- $\vec v(t)$
- $\vec r(t)$
- the trajectory of motion
- the work done by the force at time $t = 3\ \text{s}$
- check the consistency with the work-energy theorem

---

<details>
<summary>📖 🔎 Click to see theory</summary>

For a constant force:

$$
\vec F = m\vec a
$$

So acceleration is constant:

$$
\vec a = \frac{\vec F}{m}
$$

Then:

- integrate acceleration to get velocity
- integrate velocity to get position
- work can be found from:

$$
W = \vec F \cdot \Delta \vec r
$$

Also, the work-energy theorem says:

$$
W = \Delta K
$$

</details>

---

## 🚀 Step 1 — Acceleration

Using Newton’s second law:

$$
\vec a = \frac{\vec F}{m}
$$

Substitute:

$$
\vec a = \frac{(6,\ 2)}{2}
$$

$$
\vec a = (3,\ 1)\ \text{m/s}^2
$$

---

## ✅ Acceleration Function

$$
\boxed{\vec a(t) = (3,\ 1)}
$$

---

## 🚀 Step 2 — Velocity

Integrate acceleration:

$$
\vec v(t) = \vec v_0 + \vec a t
$$

Substitute:

$$
\vec v(t) = (1,\ -1) + (3,\ 1)t
$$

So:

$$
\vec v(t) = (1 + 3t,\ -1 + t)
$$

---

## ✅ Velocity Function

$$
\boxed{\vec v(t) = (1 + 3t,\ -1 + t)}
$$

---

## 🚀 Step 3 — Position

Integrate velocity:

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2}\vec a t^2
$$

Substitute:

$$
\vec r(t) = (0,\ 0) + (1,\ -1)t + \frac{1}{2}(3,\ 1)t^2
$$

So:

$$
x(t) = t + \frac{3}{2}t^2
$$

$$
y(t) = -t + \frac{1}{2}t^2
$$

Thus:

$$
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)
$$

---

## ✅ Position Function

$$
\boxed{
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)
}
$$

---

## 🚀 Step 4 — Trajectory of Motion

We eliminate $t$.

From:

$$
x = t + \frac{3}{2}t^2
$$

$$
y = -t + \frac{1}{2}t^2
$$

A simple way is to combine them.

Multiply the second equation by $3$:

$$
3y = -3t + \frac{3}{2}t^2
$$

Now subtract from $x$:

$$
x - 3y = t + \frac{3}{2}t^2 - \left(-3t + \frac{3}{2}t^2\right)
$$

$$
x - 3y = 4t
$$

So:

$$
t = \frac{x - 3y}{4}
$$

This shows the motion follows a **parabolic trajectory**.

---

## 🚀 Step 5 — Work Done by the Force at $t = 3\ \text{s}$

First find displacement at $t = 3$:

$$
x(3) = 3 + \frac{3}{2}(9) = 3 + 13.5 = 16.5
$$

$$
y(3) = -3 + \frac{1}{2}(9) = -3 + 4.5 = 1.5
$$

So:

$$
\Delta \vec r = (16.5,\ 1.5)
$$

Now calculate work:

$$
W = \vec F \cdot \Delta \vec r
$$

$$
W = (6,\ 2)\cdot(16.5,\ 1.5)
$$

$$
W = 6(16.5) + 2(1.5)
$$

$$
W = 99 + 3 = 102\ \text{J}
$$

---

## ✅ Work Result

$$
\boxed{W = 102\ \text{J}}
$$

---

## 🚀 Step 6 — Check with Work-Energy Theorem

Initial kinetic energy:

$$
K_0 = \frac{1}{2}m v_0^2
$$

Initial speed squared:

$$
v_0^2 = 1^2 + (-1)^2 = 2
$$

So:

$$
K_0 = \frac{1}{2}(2)(2) = 2\ \text{J}
$$

---

Velocity at $t=3$:

$$
\vec v(3) = (1+9,\ -1+3) = (10,\ 2)
$$

Speed squared:

$$
v^2 = 10^2 + 2^2 = 104
$$

Final kinetic energy:

$$
K_3 = \frac{1}{2}(2)(104) = 104\ \text{J}
$$

Change in kinetic energy:

$$
\Delta K = 104 - 2 = 102\ \text{J}
$$

So:

$$
W = \Delta K
$$

✔ The work-energy theorem is satisfied.

---

## ✅ Final Results

### Acceleration

$$
\boxed{\vec a(t) = (3,\ 1)}
$$

### Velocity

$$
\boxed{\vec v(t) = (1+3t,\ -1+t)}
$$

### Position

$$
\boxed{
\vec r(t) = \left(t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2\right)
}
$$

### Work at $t=3\ \text{s}$

$$
\boxed{W = 102\ \text{J}}
$$

### Work-Energy Theorem

$$
\boxed{W = \Delta K = 102\ \text{J}}
$$

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Constant force F] --> B[Constant acceleration a]
    B --> C[Integrate to get velocity]
    C --> D[Integrate to get position]
    D --> E[Find displacement at t = 3 s]
    E --> F[Compute work W = F · Δr]
    F --> G[Compare with ΔK]