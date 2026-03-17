# 🐜 Problem 10 — Infinite Series

An ant starts at the origin and moves according to the pattern:

- \(1\) m east
- \(1/2\) m north
- \(1/3\) m west
- \(1/4\) m south
- \(1/5\) m east
- and so on

We want to determine the **final position** of the ant.

---

## 📌 Step 1: Separate horizontal and vertical motion

The horizontal motion is:

- east: positive \(x\)
- west: negative \(x\)

So the \(x\)-coordinate is:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

The vertical motion is:

- north: positive \(y\)
- south: negative \(y\)

So the \(y\)-coordinate is:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

---

## 🧠 Step 2: Recognize the series for the x-coordinate

The series

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

is the well-known Gregory–Leibniz series:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots = \frac{\pi}{4}
$$

Therefore:

$$
x = \frac{\pi}{4}
$$

---

## 🧠 Step 3: Recognize the series for the y-coordinate

We write:

$$
y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots\right)
$$

The alternating harmonic series is:

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

So:

$$
y = \frac{1}{2}\ln 2
$$

---

## 🔍 Step 4: Final position

The final position of the ant is:

$$
\left(\frac{\pi}{4}, \frac{1}{2}\ln 2\right)
$$

---

## 🎯 Final Result

$$
x = \frac{\pi}{4}
$$

$$
y = \frac{1}{2}\ln 2
$$

So the final position is:

$$
\boxed{\left(\frac{\pi}{4}, \frac{1}{2}\ln 2\right)}
$$

---

## 💡 Interpretation

The motion converges because both coordinate sums are convergent alternating series.

- The horizontal position converges to:

$$
\frac{\pi}{4}
$$

- The vertical position converges to:

$$
\frac{1}{2}\ln 2
$$

So even though the ant makes infinitely many moves, its final position is finite.