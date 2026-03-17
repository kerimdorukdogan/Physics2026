# 📦 Problem 9 — Optimization Problem

A rectangle is under the curve

$$
y = 3 - x^2
$$

in the first quadrant.

We want to find the dimensions of the rectangle with the **maximum area**.

---

## 📌 Step 1: Describe the rectangle

Let the upper-right corner of the rectangle be at the point

$$
(x,y)
$$

on the curve

$$
y = 3 - x^2
$$

Since the rectangle is in the first quadrant:

- width = \(x\)
- height = \(y = 3 - x^2\)

So the area is

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

---

## 🔍 Step 2: Differentiate the area function

To maximize the area, compute the derivative:

$$
A'(x) = \frac{d}{dx}(3x - x^3)
$$

$$
A'(x) = 3 - 3x^2
$$

Set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

Since we are in the first quadrant:

$$
x = 1
$$

---

## ✏️ Step 3: Find the corresponding height

Substitute \(x = 1\) into the curve:

$$
y = 3 - x^2
$$

$$
y = 3 - 1^2
$$

$$
y = 2
$$

---

## ✅ Step 4: Verify it is a maximum

Second derivative:

$$
A''(x) = -6x
$$

At \(x = 1\):

$$
A''(1) = -6 < 0
$$

So the area is indeed **maximum** at \(x=1\).

---

## 🎯 Final Result

The rectangle with maximum area has:

- width:

$$
x = 1
$$

- height:

$$
y = 2
$$

So the dimensions are:

$$
\boxed{1 \times 2}
$$

The maximum area is:

$$
A_{\max} = 1 \cdot 2 = 2
$$

---

## 💡 Interpretation

The area depends on the balance between width and height.

- If the rectangle is too wide, the height becomes small.
- If it is too narrow, the width is too small.

The optimal balance occurs at:

$$
x = 1,\quad y = 2
$$