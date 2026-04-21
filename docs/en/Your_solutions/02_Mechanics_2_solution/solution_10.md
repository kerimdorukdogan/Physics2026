# 🌌 10. Force Field and Power

---

## 📌 Problem

In a certain force field, the equations of motion of a particle with mass $m = 0.5\ \text{kg}$ are:

$$
x = 5t^2 - t,\qquad y = 2t^3,\qquad z = -3t + 2
$$

Find:

- the particle's **velocity**
- the particle's **momentum**
- the particle's **acceleration**
- the **force** acting on the particle
- the **power** transferred by the field to the particle

---

<details>
<summary>📖 🔎 Click to see theory</summary>

For position vector:

$$
\vec r(t) = (x(t), y(t), z(t))
$$

we use:

- Velocity:

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

- Acceleration:

$$
\vec a(t) = \frac{d\vec v}{dt}
$$

- Momentum:

$$
\vec p(t) = m\vec v(t)
$$

- Force:

$$
\vec F(t) = m\vec a(t)
$$

- Power:

$$
P(t) = \vec F \cdot \vec v
$$

</details>

---

## 🚀 Step 1 — Position Vector

The position is:

$$
\vec r(t) = (5t^2 - t,\ 2t^3,\ -3t + 2)
$$

---

## 🚀 Step 2 — Velocity

Differentiate each component:

$$
v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1
$$

$$
v_y = \frac{d}{dt}(2t^3) = 6t^2
$$

$$
v_z = \frac{d}{dt}(-3t + 2) = -3
$$

So the velocity vector is:

$$
\vec v(t) = (10t - 1,\ 6t^2,\ -3)
$$

---

## 🚀 Step 3 — Momentum

Since $m = 0.5\ \text{kg}$:

$$
\vec p(t) = m\vec v(t)
$$

$$
\vec p(t) = 0.5(10t - 1,\ 6t^2,\ -3)
$$

$$
\vec p(t) = (5t - 0.5,\ 3t^2,\ -1.5)
$$

---

## 🚀 Step 4 — Acceleration

Differentiate velocity:

$$
a_x = \frac{d}{dt}(10t - 1) = 10
$$

$$
a_y = \frac{d}{dt}(6t^2) = 12t
$$

$$
a_z = \frac{d}{dt}(-3) = 0
$$

So:

$$
\vec a(t) = (10,\ 12t,\ 0)
$$

---

## 🚀 Step 5 — Force

Use Newton's second law:

$$
\vec F(t) = m\vec a(t)
$$

$$
\vec F(t) = 0.5(10,\ 12t,\ 0)
$$

$$
\vec F(t) = (5,\ 6t,\ 0)
$$

---

## 🚀 Step 6 — Power

Power is the dot product:

$$
P(t) = \vec F \cdot \vec v
$$

Substitute:

$$
P(t) = (5,\ 6t,\ 0)\cdot(10t - 1,\ 6t^2,\ -3)
$$

Compute term by term:

$$
P(t) = 5(10t - 1) + 6t(6t^2) + 0(-3)
$$

$$
P(t) = 50t - 5 + 36t^3
$$

So:

$$
P(t) = 36t^3 + 50t - 5
$$

---

## ✅ Final Results

### Velocity

$$
\boxed{\vec v(t) = (10t - 1,\ 6t^2,\ -3)}
$$

### Momentum

$$
\boxed{\vec p(t) = (5t - 0.5,\ 3t^2,\ -1.5)}
$$

### Acceleration

$$
\boxed{\vec a(t) = (10,\ 12t,\ 0)}
$$

### Force

$$
\boxed{\vec F(t) = (5,\ 6t,\ 0)}
$$

### Power

$$
\boxed{P(t) = 36t^3 + 50t - 5}
$$

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Position r(t)] --> B[Differentiate]
    B --> C[Velocity v(t)]
    C --> D[Differentiate]
    D --> E[Acceleration a(t)]
    C --> F[Multiply by m]
    F --> G[Momentum p(t)]
    E --> H[Multiply by m]
    H --> I[Force F(t)]
    I --> J[Dot with v(t)]
    J --> K[Power P(t)]