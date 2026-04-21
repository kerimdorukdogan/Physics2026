# ⏱️ 11. Dynamics with a Time-Dependent Force

---

## 📌 Problem

A particle of mass

$$
m = 3\ \text{kg}
$$

moves in a force field that depends on time:

$$
\vec F(t) = (15t,\ 3t - 12,\ -6t^2)\ \text{N}
$$

Initial conditions:

$$
\vec r_0 = (5,\ 2,\ -3)\ \text{m}
$$

$$
\vec v_0 = (2,\ 0,\ 1)\ \text{m/s}
$$

Find the dependence of the particle’s **velocity** and **position** on time.

---

<details>
<summary>📖 🔎 Click to see theory</summary>

Using Newton’s second law:

$$
\vec F = m\vec a
$$

So:

$$
\vec a(t) = \frac{\vec F(t)}{m}
$$

Then:

- integrate acceleration to get velocity
- integrate velocity to get position

</details>

---

## 🚀 Step 1 — Find the Acceleration

Given:

$$
\vec F(t) = (15t,\ 3t - 12,\ -6t^2)
$$

and

$$
m = 3
$$

So:

$$
\vec a(t) = \frac{\vec F(t)}{m}
$$

$$
\vec a(t) = \left(\frac{15t}{3},\ \frac{3t-12}{3},\ \frac{-6t^2}{3}\right)
$$

$$
\vec a(t) = (5t,\ t-4,\ -2t^2)
$$

---

## 🚀 Step 2 — Find the Velocity

We integrate each component of acceleration.

### x-component

$$
a_x = 5t
$$

$$
v_x(t) = \int 5t\,dt = \frac{5}{2}t^2 + C_1
$$

Using:

$$
v_x(0) = 2
$$

we get:

$$
C_1 = 2
$$

So:

$$
v_x(t) = \frac{5}{2}t^2 + 2
$$

---

### y-component

$$
a_y = t - 4
$$

$$
v_y(t) = \int (t-4)\,dt = \frac{1}{2}t^2 - 4t + C_2
$$

Using:

$$
v_y(0) = 0
$$

we get:

$$
C_2 = 0
$$

So:

$$
v_y(t) = \frac{1}{2}t^2 - 4t
$$

---

### z-component

$$
a_z = -2t^2
$$

$$
v_z(t) = \int -2t^2\,dt = -\frac{2}{3}t^3 + C_3
$$

Using:

$$
v_z(0) = 1
$$

we get:

$$
C_3 = 1
$$

So:

$$
v_z(t) = -\frac{2}{3}t^3 + 1
$$

---

## ✅ Velocity Function

$$
\boxed{
\vec v(t) =
\left(
\frac{5}{2}t^2 + 2,\ 
\frac{1}{2}t^2 - 4t,\ 
-\frac{2}{3}t^3 + 1
\right)
}
$$

---

## 🚀 Step 3 — Find the Position

Now integrate velocity.

### x-component

$$
x(t) = \int \left(\frac{5}{2}t^2 + 2\right) dt
$$

$$
x(t) = \frac{5}{6}t^3 + 2t + D_1
$$

Using:

$$
x(0) = 5
$$

we get:

$$
D_1 = 5
$$

So:

$$
x(t) = \frac{5}{6}t^3 + 2t + 5
$$

---

### y-component

$$
y(t) = \int \left(\frac{1}{2}t^2 - 4t\right) dt
$$

$$
y(t) = \frac{1}{6}t^3 - 2t^2 + D_2
$$

Using:

$$
y(0) = 2
$$

we get:

$$
D_2 = 2
$$

So:

$$
y(t) = \frac{1}{6}t^3 - 2t^2 + 2
$$

---

### z-component

$$
z(t) = \int \left(-\frac{2}{3}t^3 + 1\right) dt
$$

$$
z(t) = -\frac{1}{6}t^4 + t + D_3
$$

Using:

$$
z(0) = -3
$$

we get:

$$
D_3 = -3
$$

So:

$$
z(t) = -\frac{1}{6}t^4 + t - 3
$$

---

## ✅ Position Function

$$
\boxed{
\vec r(t) =
\left(
\frac{5}{6}t^3 + 2t + 5,\ 
\frac{1}{6}t^3 - 2t^2 + 2,\ 
-\frac{1}{6}t^4 + t - 3
\right)
}
$$

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Force F(t)] --> B[Divide by mass]
    B --> C[Acceleration a(t)]
    C --> D[Integrate]
    D --> E[Velocity v(t)]
    E --> F[Use initial velocity]
    E --> G[Integrate again]
    G --> H[Position r(t)]
    H --> I[Use initial position]