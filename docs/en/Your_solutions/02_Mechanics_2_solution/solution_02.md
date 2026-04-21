# 🧲 Section 2: Mechanics II  
## 🎵 2. Harmonic Motion

---

## 📌 Problem

> A 10 kg mass is attached to a spring and oscillates according to the equation  
>
> $$
> x(t)=0.2\cos(10\pi t)
> $$
>
> (in meters).
>
> What is the spring constant $k$?  
> What is the total mechanical energy of the system?

---

<details>
<summary>📖 🔎 Click to see theory</summary>

### Simple Harmonic Motion Formula

The general form of SHM is:

$$
x(t)=A\cos(\omega t)
$$

Where:

- $A$ = amplitude
- $\omega$ = angular frequency
- $m$ = mass
- $k$ = spring constant

For a mass-spring system:

$$
\omega=\sqrt{\frac{k}{m}}
$$

So:

$$
k=m\omega^2
$$

The total mechanical energy is:

$$
E=\frac{1}{2}kA^2
$$

</details>

---

## 🚀 Step 1 — Identify the given values

From the equation

$$
x(t)=0.2\cos(10\pi t)
$$

we compare with

$$
x(t)=A\cos(\omega t)
$$

So we get:

- Amplitude:

$$
A=0.2\ \text{m}
$$

- Angular frequency:

$$
\omega=10\pi\ \text{rad/s}
$$

- Mass:

$$
m=10\ \text{kg}
$$

---

## 🚀 Step 2 — Find the spring constant $k$

We use:

$$
k=m\omega^2
$$

Substitute the values:

$$
k=10(10\pi)^2
$$

$$
k=10 \cdot 100\pi^2
$$

$$
k=1000\pi^2
$$

Now approximate:

$$
\pi^2 \approx 9.87
$$

$$
k \approx 1000 \cdot 9.87
$$

$$
k \approx 9870\ \text{N/m}
$$

---

### ✅ Spring Constant

$$
\boxed{k = 1000\pi^2\ \text{N/m} \approx 9870\ \text{N/m}}
$$

---

## 🚀 Step 3 — Find the total mechanical energy

We use:

$$
E=\frac{1}{2}kA^2
$$

Substitute:

$$
E=\frac{1}{2}(1000\pi^2)(0.2)^2
$$

Since

$$
(0.2)^2=0.04
$$

then:

$$
E=\frac{1}{2}(1000\pi^2)(0.04)
$$

$$
E=500\pi^2 \cdot 0.04
$$

$$
E=20\pi^2
$$

Now approximate:

$$
E \approx 20 \cdot 9.87
$$

$$
E \approx 197.4\ \text{J}
$$

---

### ✅ Total Mechanical Energy

$$
\boxed{E = 20\pi^2\ \text{J} \approx 197.4\ \text{J}}
$$

---

## 📊 Quick Summary

| Quantity | Value |
|----------|-------|
| Mass | $10\ \text{kg}$ |
| Amplitude | $0.2\ \text{m}$ |
| Angular frequency | $10\pi\ \text{rad/s}$ |
| Spring constant | $1000\pi^2\ \text{N/m}$ |
| Total energy | $20\pi^2\ \text{J}$ |

---

## 🧠 Physical Insight

- The amplitude tells us the **maximum displacement**
- The angular frequency tells us how **fast the oscillation is**
- A larger $k$ means a **stiffer spring**
- The total mechanical energy stays constant in ideal SHM

---

## 🔁 Visual Flow

```mermaid
flowchart TD
    A[x(t)=0.2cos(10πt)] --> B[A = 0.2 m]
    A --> C[ω = 10π rad/s]
    B --> D[E = 1/2 kA^2]
    C --> E[k = mω^2]
    E --> F[k = 1000π^2 N/m]
    D --> G[E = 20π^2 J]