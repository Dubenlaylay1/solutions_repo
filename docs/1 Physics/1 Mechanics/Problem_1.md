 # PROBLEM 1

# Investigating the Range as a Function of the Angle of Projection

## Motivation

Projectile motion, while seemingly simple, offers a rich playground for exploring fundamental principles of physics. The problem is straightforward: analyze how the range of a projectile depends on its angle of projection. This study helps us understand various real-world applications, such as ballistics, sports science, and engineering problems.

## 1. Theoretical Foundation

The motion of a projectile launched from the ground at an initial speed $v_0$ and an angle $\theta$ is governed by the equations of motion:

### Equations of Motion

**Horizontal Motion:**

$$ x = v_0 \cos(\theta) t $$

**Vertical Motion:**

$$ y = v_0 \sin(\theta) t - \frac{1}{2}gt^2 $$



where:

- $$ v_0 $$ is the initial velocity (m/s),

- $$ \theta $$ is the launch angle (degrees),

- $$ g $$ is the acceleration due to gravity (9.81 m/s²),

- $$ t $$ is the time (s).

### Derivation of the Range Formula

To find the range $$ R $$, we first determine the total time of flight by setting $$ y = 0 $$:



$$ t = \frac{2v_0 \sin(\theta)}{g} $$



Substituting this into the horizontal motion equation:



$$ R = v_0 \cos(\theta) \cdot \frac{2v_0 \sin(\theta)}{g} $$





$$ R = \frac{v_0^2 \sin(2\theta)}{g} $$



This equation shows that:


- The maximum range occurs at $$\theta = 45°$$.

- The range is symmetric around 45° (i.e., 0 and 90° -  give the same range).

- Higher initial velocity increases the range.

## 2. Analysis of the Range

We will analyze how the range depends on the launch angle using a computational approach.

## 3. Implementation (Python Simulation)

Below is a Python script to simulate and visualize the range as a function of the launch angle.

https://colab.research.google.com/drive/1f7K3sSSgZ2bpgStDb-Z8ROfXPNHrlTRw?usp=sharing

## 4. Results and Discussion

The plot shows that the range is maximum at 45°.



Higher initial velocity shifts the curve upwards, increasing the range.

## 5. Practical Applications

This model can be adapted for various real-world applications:

- **Sports Science**: Calculating optimal angles for throwing or kicking a ball.

- **Ballistics**: Designing projectile trajectories for military and engineering purposes.

- **Space Exploration**: Computing launch angles for rockets and satellites.

## 6. Limitations and Further Improvements

- **Air Resistance**: The model assumes no air resistance, which is unrealistic for real-world projectiles.

- **Uneven Terrain**: The analysis assumes a flat ground; including varying terrain would improve accuracy.

- **Wind Effects**: External forces such as wind can significantly alter the trajectory.

## Conclusion

This analysis provides insights into how projectile range depends on launch angle. Future improvements could incorporate air resistance, wind effects, and variable gravity to create a more realistic model.
