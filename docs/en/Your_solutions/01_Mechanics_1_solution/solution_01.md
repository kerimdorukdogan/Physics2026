# 🚀 Problem 1 — Projectile Motion

A projectile is fired from the ground with initial speed

$$
v_0 = 100 \text{ m/s}
$$

at an angle

$$
\theta = 37^\circ
$$

above the horizontal. We assume **no air resistance**.

We want to determine:

- the differential equations of motion in the horizontal and vertical directions
- the time of flight
- the maximum height
- the range

---

## 📌 Given

| Quantity | Value |
|----------|-------|
| Initial speed | $100\ \text{m/s}$ |
| Launch angle | $37^\circ$ |
| Gravity | $g = 9.81\ \text{m/s}^2$ |

---

## 📈 Trajectory Sketch

```text
                    •
                 •
              •
           •
        •
     •
  •
•------------------------------------------→ x
 \ 37°
  \
   \
    ↗ initial velocity
```

The projectile follows a **parabolic path**:
- horizontal motion is uniform
- vertical motion is affected by gravity

---

## 🧠 Key Concepts

### Initial velocity components

$$
v_{0x} = v_0 \cos\theta
$$

$$
v_{0y} = v_0 \sin\theta
$$

### Differential equations of motion

Horizontal direction:

$$
\frac{d^2x}{dt^2} = 0
$$

Vertical direction:

$$
\frac{d^2y}{dt^2} = -g
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Resolve the initial velocity into components

$$
v_{0x} = 100 \cos 37^\circ
$$

$$
v_{0y} = 100 \sin 37^\circ
$$

Using approximate values:

$$
\cos 37^\circ \approx 0.7986
\qquad
\sin 37^\circ \approx 0.6018
$$

So:

$$
v_{0x} \approx 79.86\ \text{m/s}
$$

$$
v_{0y} \approx 60.18\ \text{m/s}
$$

---

### 2️⃣ Write the equations of motion

Since there is no air resistance:

- the horizontal acceleration is zero
- the vertical acceleration is \(-g\)

Therefore:

$$
\frac{d^2x}{dt^2} = 0
$$

$$
\frac{d^2y}{dt^2} = -g
$$

Integrating once gives the velocity components:

$$
\frac{dx}{dt} = v_{0x}
$$

$$
\frac{dy}{dt} = v_{0y} - gt
$$

Integrating again gives the position equations:

$$
x(t) = v_{0x} t
$$

$$
y(t) = v_{0y} t - \frac{1}{2}gt^2
$$

So numerically:

$$
x(t) \approx 79.86 t
$$

$$
y(t) \approx 60.18 t - 4.905 t^2
$$

---

### 3️⃣ Determine the time of flight

The projectile lands when:

$$
y(t) = 0
$$

So:

$$
60.18 t - 4.905 t^2 = 0
$$

Factor out \(t\):

$$
t(60.18 - 4.905 t) = 0
$$

Ignoring the trivial solution \(t=0\), we get:

$$
T = \frac{60.18}{4.905}
$$

$$
T \approx 12.27\ \text{s}
$$

---

### 4️⃣ Determine the maximum height

At the highest point, the vertical velocity is zero:

$$
v_y = v_{0y} - gt = 0
$$

So:

$$
60.18 - 9.81 t = 0
$$

$$
t = \frac{60.18}{9.81} \approx 6.13\ \text{s}
$$

Now use the formula for maximum height:

$$
H_{\max} = \frac{v_{0y}^2}{2g}
$$

$$
H_{\max} = \frac{(60.18)^2}{2 \cdot 9.81}
$$

$$
H_{\max} \approx 184.6\ \text{m}
$$

---

### 5️⃣ Determine the range

The horizontal distance traveled is:

$$
R = v_{0x} \cdot T
$$

$$
R \approx 79.86 \times 12.27
$$

$$
R \approx 979.8\ \text{m}
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Differential equation in \(x\) | $\frac{d^2x}{dt^2}=0$ |
| Differential equation in \(y\) | $\frac{d^2y}{dt^2}=-g$ |
| Time of flight | $12.27\ \text{s}$ |
| Maximum height | $184.6\ \text{m}$ |
| Range | $979.8\ \text{m}$ |

---

## 💡 Interpretation

This is a standard projectile motion problem.

- The **horizontal motion** is uniform because no horizontal force acts on the projectile.
- The **vertical motion** is uniformly accelerated downward because of gravity.
- Together, these two motions produce a **parabolic trajectory**.

---

## ✅ Final Answer

$$
\frac{d^2x}{dt^2} = 0
\qquad
\frac{d^2y}{dt^2} = -g
$$

$$
T \approx 12.27\ \text{s}
$$

$$
H_{\max} \approx 184.6\ \text{m}
$$

$$
R \approx 979.8\ \text{m}
$$