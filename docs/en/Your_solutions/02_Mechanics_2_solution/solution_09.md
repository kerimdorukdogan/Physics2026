# 🚀 9. Vertical Throw with Drag

---

## 📌 Problem

We have the equation of motion:

$$
m \frac{dv}{dt} = -mg - kv
$$

with initial conditions:

- $v(0) = v_0$
- $x(0) = 10$

Tasks:

- Solve the equation analytically  
- Determine the maximum height  
- Compare with the case without drag  
- Perform a numerical simulation  

---

<details>
<summary>📖 🔎 Click to see theory</summary>

- This is motion with **linear air resistance**  
- Drag force is proportional to velocity:

$$
F_{\text{drag}} = -kv
$$

- Total force:

$$
F = -mg - kv
$$

</details>

---

## 🚀 Step 1 — Solve the Differential Equation

Start with:

$$
m \frac{dv}{dt} = -mg - kv
$$

Divide by $m$:

$$
\frac{dv}{dt} = -g - \frac{k}{m}v
$$

This is a **first-order linear differential equation**.

---

## 🚀 Step 2 — Solution for Velocity

General solution:

$$
v(t) = -\frac{mg}{k} + \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t}
$$

---

## 🚀 Step 3 — Position Function

Integrate velocity:

$$
x(t) = x_0 + \int v(t)\,dt
$$

Result:

$$
x(t) = x_0 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)\left(1 - e^{-\frac{k}{m}t}\right) - \frac{mg}{k}t
$$

---

## 🚀 Step 4 — Maximum Height

Maximum height occurs when:

$$
v(t) = 0
$$

So:

$$
0 = -\frac{mg}{k} + \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t}
$$

Solve for $t$:

$$
e^{-\frac{k}{m}t} = \frac{mg}{k v_0 + mg}
$$

Then:

$$
t_{\text{max}} = \frac{m}{k} \ln\left(\frac{k v_0 + mg}{mg}\right)
$$

Substitute into $x(t)$ to get height.

---

## 🚀 Step 5 — Without Drag (Comparison)

If $k = 0$:

Velocity:

$$
v(t) = v_0 - gt
$$

Maximum height:

$$
h = \frac{v_0^2}{2g}
$$

---

## 🔍 Comparison

| Case | Behavior |
|------|--------|
| No drag | Symmetric motion |
| With drag | Slower upward motion |
| Max height | Smaller with drag |

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[Initial velocity v0] --> B[Gravity acts downward]
    B --> C[Drag force opposes motion]
    C --> D[Velocity decreases faster]
    D --> E[Lower maximum height]