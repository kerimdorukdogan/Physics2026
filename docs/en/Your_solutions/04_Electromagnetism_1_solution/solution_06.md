# ⚡ Field from a System of Charges — Solution

## Problem

Two point charges are given:

- +q at (-a, 0)
- +2q at (a, 0)

Find the electric field at different points.

---

## Step 1: General electric field

Electric field from a point charge:

E = kQ / r²

Vector form:

E = kQ · r_vector / r³

For charge +q at (-a, 0):

r₁ = (x + a, y)

For charge +2q at (a, 0):

r₂ = (x - a, y)

So the total field is:

E(x,y) = kq · (x + a, y) / [(x + a)² + y²]^(3/2)
       + 2kq · (x - a, y) / [(x - a)² + y²]^(3/2)

---

## Step 2: Field at point (0, y)

At x = 0:

Distance from both charges:

R = sqrt(a² + y²)

The field becomes:

Ex = -kqa / (a² + y²)^(3/2)

Ey = 3kqy / (a² + y²)^(3/2)

So:

E(0,y) = [ -kqa / (a² + y²)^(3/2) ] i
       + [ 3kqy / (a² + y²)^(3/2) ] j

Important: Ex is not zero because the charges are not equal.

---

## Step 3: Field at point (x, 0)

On the x-axis:

E(x,0) = kq · (x + a) / |x + a|³
       + 2kq · (x - a) / |x - a|³

This field has only x-component.

Ey = 0

---

## Step 4: Condition for zero field

For zero field:

Ey = 0

This requires:

y = 0

So the zero field must be on the x-axis.

Between the charges:

- distance from +q is x + a
- distance from +2q is a - x

Set magnitudes equal:

kq / (x + a)² = 2kq / (a - x)²

Cancel kq:

1 / (x + a)² = 2 / (a - x)²

Take square root:

1 / (x + a) = sqrt(2) / (a - x)

a - x = sqrt(2)(x + a)

Solving gives:

x = a(1 - sqrt(2)) / (1 + sqrt(2))

x ≈ -0.172a

---

## Zero Field Position

E = 0 at:

x ≈ -0.172a

y = 0

This point is between the charges and closer to the smaller charge +q.

---

## Step 5: Numerical calculation

Given:

a = 0.2 m  
y = 0.3 m  
q = 2 μC = 2 × 10⁻⁶ C  
k = 9 × 10⁹

For point (0, y):

a² + y² = 0.2² + 0.3²

a² + y² = 0.13

(a² + y²)^(3/2) ≈ 0.0469

---

### x-component

Ex = -kqa / (a² + y²)^(3/2)

Ex = -(9 × 10⁹)(2 × 10⁻⁶)(0.2) / 0.0469

Ex ≈ -7.7 × 10⁴ N/C

---

### y-component

Ey = 3kqy / (a² + y²)^(3/2)

Ey = 3(9 × 10⁹)(2 × 10⁻⁶)(0.3) / 0.0469

Ey ≈ 3.46 × 10⁵ N/C

---

## Final Numerical Field

E(0, 0.3) ≈ (-7.7 × 10⁴ i + 3.46 × 10⁵ j) N/C

Magnitude:

|E| ≈ 3.54 × 10⁵ N/C

---

## Step 6: Limit y >> a

If y is much larger than a:

a becomes very small compared to y.

So the charges look almost like one combined charge:

qtotal = q + 2q = 3q

Therefore:

Ey ≈ 3kq / y²

Ex ≈ -kqa / y³

The dominant field is upward, like a single charge of 3q.