# 🎯 Problem 2 — Range Optimization

For projectile motion, the range is given by

$$
R(\theta)=\frac{v_0^2\sin(2\theta)}{g}
$$

We want to show analytically that for a fixed initial velocity, the **maximum range** is obtained when the launch angle is:

$$
45^\circ
$$

---

## 📌 Given

$$
R(\theta)=\frac{v_0^2\sin(2\theta)}{g}
$$

where:

- \(v_0\) is the initial velocity
- \(g\) is gravitational acceleration
- \(\theta\) is the launch angle

---

## 🧠 Key Idea

For a fixed projectile speed, the quantities

$$
v_0^2
\quad \text{and} \quad
g
$$

are constants.

So the only part that changes with the angle is:

$$
\sin(2\theta)
$$

Therefore, maximizing the range means maximizing:

$$
\sin(2\theta)
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Focus on the variable part

The formula is

$$
R(\theta)=\frac{v_0^2}{g}\sin(2\theta)
$$

Since

$$
\frac{v_0^2}{g}
$$

is constant, the maximum value of \(R(\theta)\) is reached when \(\sin(2\theta)\) is maximum.

---

### 2️⃣ Maximum value of sine

We know that for any angle:

$$
-1 \le \sin(2\theta) \le 1
$$

The largest possible value is:

$$
\sin(2\theta)=1
$$

This happens when:

$$
2\theta = 90^\circ
$$

So:

$$
\theta = 45^\circ
$$

---

### 3️⃣ Maximum range

Substitute this into the formula:

$$
R_{\max}=\frac{v_0^2\sin(90^\circ)}{g}
$$

Since:

$$
\sin(90^\circ)=1
$$

we obtain:

$$
R_{\max}=\frac{v_0^2}{g}
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Angle for maximum range | 45° |
| Maximum range | \( \frac{v_0^2}{g} \) |

---

## 💡 Interpretation

The projectile range is largest when the angle balances horizontal and vertical motion in the most effective way.

That happens at:

$$
45^\circ
$$

because this makes

$$
\sin(2\theta)=1
$$

which is the maximum possible value.

---

## ✅ Final Answer

The range is maximum when:

$$
\theta = 45^\circ
$$

and the corresponding maximum range is:

$$
R_{\max}=\frac{v_0^2}{g}
$$