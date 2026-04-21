# 🌊 3. Superposition Principle

---

## 📌 Problem

Two waves are described by:

$$
y_1(x,t) = A\sin(kx - \omega t)
$$

and

$$
y_2(x,t) = A\sin(kx + \omega t)
$$

Find:

- the equation of the resulting **standing wave**
- the positions of the **nodes**

---

<details>
<summary>📖 🔎 Click to see theory</summary>

When two waves with the same amplitude and frequency travel in opposite directions, they combine by **superposition** and form a **standing wave**.

We use the trigonometric identity:

$$
\sin(\alpha - \beta) + \sin(\alpha + \beta) = 2\sin\alpha \cos\beta
$$

</details>

---

## 🚀 Step 1 — Add the Two Waves

The total wave is:

$$
y(x,t) = y_1(x,t) + y_2(x,t)
$$

Substitute:

$$
y(x,t) = A\sin(kx - \omega t) + A\sin(kx + \omega t)
$$

Factor out $A$:

$$
y(x,t) = A\left[\sin(kx - \omega t) + \sin(kx + \omega t)\right]
$$

---

## 🚀 Step 2 — Use the Trigonometric Identity

Using

$$
\sin(\alpha - \beta) + \sin(\alpha + \beta) = 2\sin\alpha \cos\beta
$$

with

- $\alpha = kx$
- $\beta = \omega t$

we get:

$$
y(x,t) = 2A\sin(kx)\cos(\omega t)
$$

---

## ✅ Standing Wave Equation

$$
\boxed{y(x,t) = 2A\sin(kx)\cos(\omega t)}
$$

---

## 🚀 Step 3 — Find the Nodes

Nodes are points that never move, so the displacement must always be zero.

This happens when:

$$
\sin(kx) = 0
$$

We know:

$$
\sin(kx) = 0 \quad \Rightarrow \quad kx = n\pi
$$

where

$$
n = 0,1,2,3,\dots
$$

So:

$$
x_n = \frac{n\pi}{k}
$$

Since

$$
k = \frac{2\pi}{\lambda}
$$

we can also write:

$$
x_n = \frac{n\lambda}{2}
$$

---

## ✅ Node Positions

$$
\boxed{x_n = \frac{n\pi}{k} = \frac{n\lambda}{2}}
$$

for

$$
n = 0,1,2,3,\dots
$$

---

## 🎯 Visual (Standing Wave)

<pre>
Node      Antinode      Node      Antinode      Node
|----------()-----------|----------()-----------|
</pre>

---

## 🔍 Physical Interpretation

- The two waves move in **opposite directions**
- Their superposition creates a **standing wave**
- Some points never move → **nodes**
- Some points vibrate the most → **antinodes**

In a standing wave:

- nodes are separated by:

$$
\frac{\lambda}{2}
$$

- node to antinode distance is:

$$
\frac{\lambda}{4}
$$

---

## 📊 Quick Summary

| Quantity | Result |
|----------|--------|
| Resulting wave | $y(x,t)=2A\sin(kx)\cos(\omega t)$ |
| Node condition | $\sin(kx)=0$ |
| Node positions | $x_n=\frac{n\pi}{k}=\frac{n\lambda}{2}$ |

---

## 📝 What we learned

- Two opposite traveling waves form a standing wave  
- The standing wave has fixed nodes  
- Nodes occur every half wavelength  

---