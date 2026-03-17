# 🚣 Problem 5 — Relative Velocity

A river flows east with speed

$$
2 \text{ m/s}
$$

A boat can travel at

$$
5 \text{ m/s}
$$

in still water.

The boat wants to go **directly north** across the river.

The river is

$$
200 \text{ m}
$$

wide.

We want to determine:

- the direction the boat should head
- the time needed to cross the river

---

## 📌 Given

| Quantity | Value |
|----------|-------|
| River speed | $2\ \text{m/s}$ east |
| Boat speed in still water | $5\ \text{m/s}$ |
| River width | $200\ \text{m}$ |

---

## 🧭 Velocity Sketch

```text
                 North
                   ↑
                   |
                   |   Resultant motion
                   |   straight across
                   |
Boat heading        ↖
(against current)    \
                       \
------------------------+------------------------→ East
                        \
                         \ River current = 2 m/s
                          →
```

The boat must aim slightly **west of north** so that its westward component cancels the river current.

---

## 🧠 Key Concepts

To move directly north, the horizontal component of the boat's velocity must cancel the eastward river flow.

Let \(\theta\) be the angle **west of north**.

Then:

$$
5\sin\theta = 2
$$

The northward component of the boat's velocity is:

$$
v_n = 5\cos\theta
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Find the heading angle

We use the condition that the westward component must balance the river current:

$$
5\sin\theta = 2
$$

So:

$$
\sin\theta = \frac{2}{5}
$$

$$
\theta = \sin^{-1}\left(\frac{2}{5}\right)
$$

$$
\theta \approx 23.6^\circ
$$

So the boat must head:

$$
23.6^\circ \text{ west of north}
$$

---

### 2️⃣ Find the northward speed

The northward component is:

$$
v_n = 5\cos\theta
$$

Using:

$$
\cos 23.6^\circ \approx 0.9165
$$

we get:

$$
v_n \approx 5(0.9165)
$$

$$
v_n \approx 4.58\ \text{m/s}
$$

---

### 3️⃣ Compute the crossing time

The time to cross is:

$$
t = \frac{\text{distance}}{\text{speed}}
$$

So:

$$
t = \frac{200}{4.58}
$$

$$
t \approx 43.7\ \text{s}
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Heading angle | $23.6^\circ$ west of north |
| Northward speed | $4.58\ \text{m/s}$ |
| Crossing time | $43.7\ \text{s}$ |

---

## 💡 Interpretation

The river pushes the boat toward the east.  

To cancel this effect, the boat must aim slightly **upstream**, meaning slightly **west of north**.

This way, the resultant motion is exactly straight across the river.

---

## ✅ Final Answer

The boat should head:

$$
23.6^\circ \text{ west of north}
$$

and the crossing time is:

$$
43.7\ \text{s}
$$