# 🧭 Problem 3 — Path Intersection

Alice moves along the path:

$$
A(t) = (2 + t,\; 8 - 3t)
$$

Bob moves along the path:

$$
B(t) = (2t - 1,\; 2t + 2)
$$

We want to determine whether their paths intersect.  
If yes, we must find when and where they collide.  
If not, we find the minimum distance and when it occurs.

---

## 📌 Given

Alice:

$$
A(t) = (2+t,\;8-3t)
$$

Bob:

$$
B(t) = (2t-1,\;2t+2)
$$

---

## 🧠 Key Concept

The distance between the two moving points is based on the difference of their coordinates.

Define the relative position:

$$
\Delta(t) = A(t) - B(t)
$$

Then the squared distance is:

$$
D^2(t) = (\Delta x)^2 + (\Delta y)^2
$$

We minimize \(D^2(t)\), because minimizing \(D^2\) also minimizes \(D\).

---

## 🔍 Step-by-Step Solution

### 1️⃣ Relative position

For the \(x\)-coordinates:

$$
\Delta x = (2+t) - (2t-1) = 3 - t
$$

For the \(y\)-coordinates:

$$
\Delta y = (8-3t) - (2t+2) = 6 - 5t
$$

So:

$$
\Delta(t) = (3-t,\;6-5t)
$$

---

### 2️⃣ Check for collision

A collision would require:

$$
3-t = 0
$$

and

$$
6-5t = 0
$$

From the first equation:

$$
t = 3
$$

From the second equation:

$$
t = \frac{6}{5}
$$

These are not equal, so there is **no collision**.

---

### 3️⃣ Build the squared distance

$$
D^2(t) = (3-t)^2 + (6-5t)^2
$$

Expand:

$$
D^2(t) = (t^2 - 6t + 9) + (25t^2 - 60t + 36)
$$

$$
D^2(t) = 26t^2 - 66t + 45
$$

---

### 4️⃣ Minimize the squared distance

Differentiate:

$$
\frac{d}{dt}D^2(t) = 52t - 66
$$

Set equal to zero:

$$
52t - 66 = 0
$$

$$
t = \frac{66}{52} = \frac{33}{26}
$$

So the minimum distance occurs at:

$$
t = \frac{33}{26}
$$

---

### 5️⃣ Compute the minimum distance

Substitute into the coordinate differences:

$$
\Delta x = 3 - \frac{33}{26} = \frac{45}{26}
$$

$$
\Delta y = 6 - 5\cdot\frac{33}{26} = \frac{156-165}{26} = -\frac{9}{26}
$$

Thus:

$$
D_{\min}^2 = \left(\frac{45}{26}\right)^2 + \left(-\frac{9}{26}\right)^2
$$

$$
D_{\min}^2 = \frac{2025 + 81}{676} = \frac{2106}{676}
$$

$$
D_{\min} = \frac{\sqrt{2106}}{26} \approx 1.76
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Collision? | No |
| Time of minimum distance | $\frac{33}{26}$ |
| Minimum distance | $\frac{\sqrt{2106}}{26} \approx 1.76$ |

---

## 💡 Interpretation

Alice and Bob do **not** arrive at the same point at the same time.  
However, their paths come closest at:

$$
t=\frac{33}{26}
$$

with a minimum separation of about:

$$
1.76
$$