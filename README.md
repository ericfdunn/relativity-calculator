
# Special Relativity Calculator

special-relativity-calculator is a project to do some basic lorentz contraction calculations under universes with different fundamental constants. Calculations and plots will be done in Jupyter and then presented below.

## The Equations

### Length Contraction

The [Lorentz contraction](https://en.wikipedia.org/wiki/Lorentz_transformation) equation is given by:

$$ L = L_0 \sqrt{1 - \frac{v^2}{c^2}} $$

Where:

- $L$ is the length of the object as measured in the frame where the object is moving.
- $L_0$ is the proper length or rest length of the object (the length of the object in the frame where it is at rest).
- $v$ is the relative velocity between the observer and the moving frame.
- $c$ is the speed of light in a vacuum.

### Time Dilation

Relativisitic [time dilation](https://en.wikipedia.org/wiki/Time_dilation) occurs due to a number of effects that curve space-time. Solving the [Einstein equations](https://en.wikipedia.org/wiki/Einstein_field_equations) for all of the effects is far beyond me and maybe not even possible, so we consider each aspect individually. Each equation below assumes all other factors are held constant. We will calculate each effect separately and then multiply the effects together to arraive at an approximation that ignores any interactions, which is probably reasonable for small changes in the parameters.

**The velocity time dilation:**

$$ \frac{\Delta t}{\Delta t_0} = \frac{1}{\sqrt{1 - \frac{v^2}{c^2}}} $$

Where:
  - $\Delta t$ is the time interval measured in the moving frame (also known as dilated time).
  - $\Delta t_0$ is the time interval measured in the rest frame (also known as proper time).
  - $v$ is the relative velocity between the observer and the moving frame.
  - $c$ is the speed of light in a vacuum.


**The gravitational time dilation:**

$$ \frac{\Delta t}{\Delta t_0} = \frac{1}{\sqrt{1 - \frac{2GM}{rc^2}}} $$

Where:
  - $\Delta t$ is the time interval as measured at a distance $r$ from the center of the massive object.
  - $\Delta t_0$ is the time interval measured far from the massive object (where the gravitational field is negligible).
  - $G$ is the gravitational constant.
  - $M$ is the mass of the object.
  - $r$ is the radial coordinate (which is analogous to the classical distance from the center of the object, but is actually a Schwarzschild coordinate).
  - $c$ is the speed of light in a vacuum.


**Cosmological constant time dilation:**

$$ \frac{\Delta t}{\Delta t_0} = \frac{1}{\sqrt{1 - \Lambda r^2 / 3}} $$

$$ \frac{\Delta t_1}{\Delta t_2} = \frac{1}{\sqrt{1 - \Lambda r_1^2 / 3}} \div \frac{1}{\sqrt{1 - \Lambda r_2^2 / 3}} $$


Where:
  - Δt₁ and Δt₂ are the proper time intervals experienced by the two observers.
  - r₁ and r₂ are their radial coordinates.
  - Λ is the [cosmological constant](https://en.wikipedia.org/wiki/Cosmological_constant).
