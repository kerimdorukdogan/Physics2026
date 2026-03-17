# 📊 Problem 7 — Elimination of Time and Interpretation of Acceleration

The path of a particle is given in parametric form:

$$
x(t) = 2t^2
$$

$$
y(t) = 3t^3
$$

We want to:

- eliminate the parameter \(t\)
- determine the trajectory
- compute \(\vec{v}(t)\), \(|\vec{v}(t)|\), \(\vec{a}(t)\), and \(|\vec{a}(t)|\)
- decide whether the acceleration is constant

---

## 📌 Given

| Quantity | Expression |
|----------|------------|
| \(x(t)\) | $2t^2$ |
| \(y(t)\) | $3t^3$ |

---

## 📈 Trajectory Sketch

```text
y
↑
|
|                         •
|                    •
|               •
|          •
|      •
|   •
| •
+------------------------------------→ x
```

The trajectory is a curved path opening to the right.

---

## 🧠 Key Concepts

Velocity is the derivative of position:

$$
\vec{v}(t)=\left(\frac{dx}{dt},\frac{dy}{dt}\right)
$$

Acceleration is the derivative of velocity:

$$
\vec{a}(t)=\left(\frac{d^2x}{dt^2},\frac{d^2y}{dt^2}\right)
$$

To eliminate the parameter, we express the relation between \(x\) and \(y\) directly.

---

## 🔍 Step-by-Step Solution

### 1️⃣ Eliminate the parameter \(t\)

From:

$$
x = 2t^2
$$

we obtain:

$$
t^2 = \frac{x}{2}
$$

Now square \(y\):

$$
y^2 = (3t^3)^2
$$

$$
y^2 = 9t^6
$$

Since:

$$
t^6 = (t^2)^3
$$

we get:

$$
t^6 = \left(\frac{x}{2}\right)^3
$$

Therefore:

$$
y^2 = 9\left(\frac{x}{2}\right)^3
$$

$$
y^2 = \frac{9}{8}x^3
$$

So the trajectory is:

$$
y^2 = \frac{9}{8}x^3
$$

---

### 2️⃣ Compute the velocity vector

Differentiate the position coordinates:

$$
\frac{dx}{dt} = 4t
$$

$$
\frac{dy}{dt} = 9t^2
$$

Thus:

$$
\vec{v}(t) = (4t,\;9t^2)
$$

---

### 3️⃣ Compute the speed

The magnitude of velocity is:

$$
|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec{v}(t)| = \sqrt{16t^2 + 81t^4}
$$

---

### 4️⃣ Compute the acceleration vector

Differentiate the velocity components:

$$
\frac{d}{dt}(4t) = 4
$$

$$
\frac{d}{dt}(9t^2) = 18t
$$

Therefore:

$$
\vec{a}(t) = (4,\;18t)
$$

---

### 5️⃣ Compute the magnitude of acceleration

$$
|\vec{a}(t)| = \sqrt{4^2 + (18t)^2}
$$

$$
|\vec{a}(t)| = \sqrt{16 + 324t^2}
$$

---

### 6️⃣ Is the acceleration constant?

No.

The \(x\)-component is constant:

$$
a_x = 4
$$

but the \(y\)-component depends on time:

$$
a_y = 18t
$$

Therefore, the acceleration changes with time and is **not constant**.

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Trajectory | $y^2 = \frac{9}{8}x^3$ |
| Velocity | $(4t,\;9t^2)$ |
| Speed | $\sqrt{16t^2 + 81t^4}$ |
| Acceleration | $(4,\;18t)$ |
| Acceleration magnitude | $\sqrt{16 + 324t^2}$ |
| Is acceleration constant? | No |

---

## 💡 Interpretation

The particle moves along a curved trajectory rather than a straight line.

Its acceleration is not constant because the vertical component grows with time:

$$
a_y = 18t
$$

So the motion becomes increasingly accelerated in the \(y\)-direction as time increases.

---

## ✅ Final Answer

$$
y^2 = \frac{9}{8}x^3
$$

$$
\vec{v}(t) = (4t,\;9t^2)
$$

$$
|\vec{v}(t)| = \sqrt{16t^2 + 81t^4}
$$

$$
\vec{a}(t) = (4,\;18t)
$$

$$
|\vec{a}(t)| = \sqrt{16 + 324t^2}
$$

The acceleration is **not constant**.