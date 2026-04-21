# 📈 8. Work of a Variable Force

---

## 📌 Problem

Given a one-dimensional force:

$$
F(x) = -kx
$$

- Write the **equation of motion** and solve it  
- Calculate the **work** from $0$ to $x_0$  
- Interpret the result as **potential energy**  
- Verify that $F = -\frac{dU}{dx}$  
- Draw the graph of $F(x)$ and $U(x)$  

---

<details>
<summary>📖 🔎 Click to see theory</summary>

- This is a **Hooke’s Law force** (spring force)  
- Force is proportional to displacement but opposite in direction  

$$
F(x) = -kx
$$

- Work is:

$$
W = \int F(x)\,dx
$$

</details>

---

## 🚀 Step 1 — Equation of Motion

Using Newton’s second law:

$$
m\ddot{x} = -kx
$$

Rewriting:

$$
\ddot{x} + \frac{k}{m}x = 0
$$

This is a **simple harmonic motion** equation.

---

## 🚀 Step 2 — Solve the Motion

General solution:

$$
x(t) = A\cos(\omega t) + B\sin(\omega t)
$$

where:

$$
\omega = \sqrt{\frac{k}{m}}
$$

---

## 🚀 Step 3 — Work from $0$ to $x_0$

Work is:

$$
W = \int_0^{x_0} (-kx)\,dx
$$

$$
W = -k \int_0^{x_0} x\,dx
$$

$$
W = -k \left[\frac{x^2}{2}\right]_0^{x_0}
$$

$$
W = -\frac{1}{2}k x_0^2
$$

---

## ✅ Work Result

$$
\boxed{W = -\frac{1}{2}k x_0^2}
$$

---

## 🚀 Step 4 — Potential Energy

Since:

$$
W = -\Delta U
$$

We get:

$$
U(x) = \frac{1}{2}kx^2
$$

---

## 🚀 Step 5 — Verification

Check:

$$
F = -\frac{dU}{dx}
$$

Differentiate:

$$
\frac{dU}{dx} = kx
$$

So:

$$
F = -kx
$$

✔ Verified

---

## 📊 Graph Interpretation

- $F(x) = -kx$ → straight line with negative slope  
- $U(x) = \frac{1}{2}kx^2$ → parabola  

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[F(x) = -kx] --> B[Newton: m x'' = -kx]
    B --> C[Simple Harmonic Motion]
    A --> D[Integrate force]
    D --> E[Work = -1/2 kx^2]
    E --> F[U = 1/2 kx^2]
    F --> G[Check derivative]