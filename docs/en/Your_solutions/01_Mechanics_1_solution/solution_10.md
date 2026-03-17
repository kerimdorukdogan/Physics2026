# 🌀 Problem 10 — Kinematics

The position of a point is

$$
\vec r(t) = (a \cos(\omega t),\; b \sin(\omega t),\; bt)
$$

where \(a\), \(b\), and \(\omega\) are positive constants.

We want to find:

- the trajectory
- the velocity vector
- the path length from \(t=0\) to \(t=t_0\)

---

## 1️⃣ Trajectory

From the parametric equations:

$$
x = a \cos(\omega t)
$$

$$
y = b \sin(\omega t)
$$

Divide both equations:

$$
\frac{x}{a} = \cos(\omega t)
$$

$$
\frac{y}{b} = \sin(\omega t)
$$

Now square and add:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} =
\cos^2(\omega t) + \sin^2(\omega t)
$$

Using the identity

$$
\cos^2(\omega t) + \sin^2(\omega t) = 1
$$

we obtain

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

So the projection in the \(xy\)-plane is an ellipse.

Since

$$
z = bt
$$

increases linearly with time, the full 3D trajectory is a helix.

---

## 2️⃣ Velocity vector

Velocity is the derivative of position.

Differentiate each component:

$$
\frac{dx}{dt} = -a\omega \sin(\omega t)
$$

$$
\frac{dy}{dt} = b\omega \cos(\omega t)
$$

$$
\frac{dz}{dt} = b
$$

Therefore

$$
\vec v(t) = \bigl(-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b\bigr)
$$

---

## 3️⃣ Speed

The speed is the magnitude of the velocity vector:

$$
|\vec v(t)| =
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
$$

---

## 4️⃣ Path length

The path length from \(0\) to \(t_0\) is

$$
L =
\int_0^{t_0}
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
\, dt
$$

---

## 🎯 Final Results

- Projection in the \(xy\)-plane: ellipse
- Equation of projection:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

- 3D trajectory: helix

- Velocity vector:

$$
\vec v(t) = \bigl(-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b\bigr)
$$

- Path length:

$$
L =
\int_0^{t_0}
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
\, dt
$$