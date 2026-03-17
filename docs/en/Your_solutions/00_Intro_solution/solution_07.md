# 🚲 Problem 7 – Logic & Series

A bicycle is **10 meters** from a wall and moves toward it at a constant speed of **1 m/s**.  
A fly starts from the bicycle's front wheel and flies toward the wall at **2 m/s**.  
Each time the fly reaches the wall, it instantly turns back toward the bicycle, and so on.

We want to find the **total distance traveled by the fly** before the bicycle hits the wall.

---

# 📌 Step 1: Find the time until the bicycle reaches the wall

The bicycle travels:

$$
d = 10 \text{ m}
$$

with speed:

$$
v = 1 \text{ m/s}
$$

Using:

$$
t = \frac{d}{v}
$$

we get:

$$
t = \frac{10}{1} = 10 \text{ s}
$$

⏱️ So the bicycle reaches the wall after **10 seconds**.

---

# 🪰 Step 2: Find how far the fly travels in that time

The fly moves continuously for the same total time:

$$
t = 10 \text{ s}
$$

Its speed is:

$$
v_f = 2 \text{ m/s}
$$

Using:

$$
d = vt
$$

we get:

$$
d_f = 2 \cdot 10 = 20 \text{ m}
$$

---

# ✅ Final Result

The total distance traveled by the fly is:

$$
20 \text{ m}
$$

---

# 💡 Why this works

At first, the problem looks complicated because the fly keeps going back and forth many times.  
But we do **not** need to calculate each trip separately.

The key idea is:

- the bicycle takes **10 seconds** to hit the wall
- the fly keeps flying during all those **10 seconds**
- the fly's speed is always **2 m/s**

So the total distance is simply:

$$
\text{distance} = \text{speed} \times \text{time}
$$

---

# 🚀 Final Answer

$$
\boxed{20 \text{ m}}
$$