# ⏳ Problem 6 — Variable Velocity

The velocity is given by:

$$
v(t) = t^2 + 2t - 5
$$

We also know that:

$$
x(0)=4
$$

We want to find:

- the position at \(t=3\)
- the acceleration at \(t=3\)

---

## 📌 Given

$$
v(t)=t^2+2t-5
$$

$$
x(0)=4
$$

---

## 🧠 Key Concepts

Velocity is the derivative of position:

$$
v(t)=\frac{dx}{dt}
$$

So position is found by integration.

Acceleration is the derivative of velocity:

$$
a(t)=\frac{dv}{dt}
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Find the position function

Integrate the velocity:

$$
x(t)=\int (t^2+2t-5)\,dt
$$

$$
x(t)=\frac{t^3}{3}+t^2-5t+C
$$

Use the initial condition \(x(0)=4\):

$$
4 = 0+0-0+C
$$

$$
C=4
$$

Therefore:

$$
x(t)=\frac{t^3}{3}+t^2-5t+4
$$

---

### 2️⃣ Find the position at \(t=3\)

$$
x(3)=\frac{3^3}{3}+3^2-5(3)+4
$$

$$
x(3)=\frac{27}{3}+9-15+4
$$

$$
x(3)=9+9-15+4
$$

$$
x(3)=7
$$

---

### 3️⃣ Find the acceleration

Differentiate the velocity:

$$
a(t)=\frac{d}{dt}(t^2+2t-5)
$$

$$
a(t)=2t+2
$$

At \(t=3\):

$$
a(3)=2(3)+2=8
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Position at \(t=3\) | $7$ |
| Acceleration at \(t=3\) | $8$ |

---

## 💡 Interpretation

The motion is **non-uniform**, because the velocity changes with time.  
The position is found by integrating the velocity, while the acceleration comes from differentiating it.