# 🧮 Problem 4 — Vector Calculus

The position of an object is given by:

$$
\vec{r}(t) = (3t^2)\,\hat{i} + (5t - 8t^2)\,\hat{j}
$$

We want to find:

- the velocity vector
- the acceleration vector

as functions of time.

---

## 📌 Given

$$
\vec{r}(t) = (3t^2)\,\hat{i} + (5t - 8t^2)\,\hat{j}
$$

---

## 🧠 Key Concepts

Velocity is the derivative of position:

$$
\vec{v}(t)=\frac{d\vec{r}}{dt}
$$

Acceleration is the derivative of velocity:

$$
\vec{a}(t)=\frac{d\vec{v}}{dt}
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Velocity vector

Differentiate each component:

$$
\frac{d}{dt}(3t^2)=6t
$$

$$
\frac{d}{dt}(5t-8t^2)=5-16t
$$

So:

$$
\vec{v}(t)=6t\,\hat{i} + (5-16t)\,\hat{j}
$$

---

### 2️⃣ Acceleration vector

Differentiate the velocity components:

$$
\frac{d}{dt}(6t)=6
$$

$$
\frac{d}{dt}(5-16t)=-16
$$

So:

$$
\vec{a}(t)=6\,\hat{i}-16\,\hat{j}
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Velocity | $6t\,\hat{i} + (5-16t)\,\hat{j}$ |
| Acceleration | $6\,\hat{i} -16\,\hat{j}$ |

---

## 💡 Interpretation

The object has a **time-dependent velocity**, but its acceleration is **constant**.  

It accelerates positively in the \(x\)-direction and negatively in the \(y\)-direction.