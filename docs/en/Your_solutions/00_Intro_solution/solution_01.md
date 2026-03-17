# 🚀 Problem 1 — Vector Algebra

We are given two vectors in three-dimensional space:

$$
\vec{a} = (2, 1, -3)
$$

$$
\vec{b} = (4, -2, 1)
$$

We want to determine:

- the **magnitudes** of both vectors
- the **dot product**
- the **cross product**

---

## 🧭 Vector Sketch

This simple sketch shows the idea of the two vectors starting from the origin.

```text
        y
        ↑
        |
        |          b = (4, -2, 1)
        |
--------O----------------------→ x
       /
      /
     a = (2, 1, -3)
```

---

## 📌 Given

| Vector | Components |
|--------|------------|
| **a**  | (2, 1, -3) |
| **b**  | (4, -2, 1) |

---

## 🧠 Key Concepts

### Magnitude of a vector

$$
|\vec{v}| = \sqrt{x^2 + y^2 + z^2}
$$

### Dot product

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

## 3️⃣ Cross Product

The cross product is computed using the determinant:

$$
\vec{a} \times \vec{b} =
\begin{vmatrix}
i & j & k \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

Now compute each component.

### I component

$$
1 \cdot 1 - (-3)(-2)
$$

$$
1 - 6 = -5
$$

### J component

$$
2 \cdot 1 - (-3)(4)
$$

$$
2 + 12 = 14
$$

### K component

$$
2(-2) - 1(4)
$$

$$
-4 - 4 = -8
$$

Therefore,

$$
\vec{a} \times \vec{b} = (-5,-14,-8)
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Magnitude of vector **a**

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

---

### 2️⃣ Magnitude of vector **b**

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

---

### 3️⃣ Dot Product

$$
\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)
$$

$$
= 8 - 2 - 3
$$

$$
= 3
$$

---

### 4️⃣ Cross Product

We compute the cross product using the determinant:

$$
\vec{a} \times \vec{b} =
\begin{vmatrix}
i & j & k \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

Expanding along the first row:

$$
\begin{aligned}
\vec{a} \times \vec{b}
&= i(1\cdot1 - (-3)(-2)) \\
&\quad - j(2\cdot1 - (-3)(4)) \\
&\quad + k(2(-2) - 1(4)) \\
&= -5i - 14j - 8k
\end{aligned}
$$

Therefore:

$$
\vec{a} \times \vec{b} = (-5,-14,-8)
$$

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Magnitude of **a** | $\sqrt{14}$ |
| Magnitude of **b** | $\sqrt{21}$ |
| Dot product | $3$ |
| Cross product | $(-5, -14, -8)$ |

---

## 💡 Interpretation

The **dot product** tells us how much two vectors point in the same direction.  

The **cross product** gives a vector that is **perpendicular to both vectors**.

These operations are fundamental in **vector algebra, mechanics, and physics**.