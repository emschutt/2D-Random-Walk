# 🌍 2D Random Walk in Python

Building on the previous Random Walk code structure, the objective is to generate a 2D random walk, visualize the its path and link it to explosive variance

## Exploding Variance in Random Walks

Although each step in a random walk is independent and has no long-term drift, the **variance of the position** grows **without bound** as time progresses. This means the **expected position** stays around zero, but the **dispersion** of possible positions **increases** with time.

Visually, this is why random walk paths spread out more and more as $t$ increases as their cumulative effect causes the position to drift farther from the origin.

In two dimensions, this idea generalizes to:

$$
E[X_t^2 + Y_t^2] = t
$$

so the **expected distance from the origin** grows proportionally to $\sqrt{t}$.
