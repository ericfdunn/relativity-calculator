
# Special Relativity Calculator

special-relativity-calculator is a project to do some basic lorentz contraction calculations under universes with different fundamental constnts. Calculations and plots will be done in Jupyter and then presented below.

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

The velocity [time dilation](https://en.wikipedia.org/wiki/Time_dilation) equation is given by:

$$ \Delta t = \frac{\Delta t_0}{\sqrt{1 - \frac{v^2}{c^2}}} $$

Where:

- $\Delta t$ is the time interval measured in the moving frame (also known as dilated time).
- $\Delta t_0$ is the time interval measured in the rest frame (also known as proper time).
- $v$ is the relative velocity between the observer and the moving frame.
- $c$ is the speed of light in a vacuum.

The gravitational time dilation formula is:

$$ \Delta t = \Delta t_0 \sqrt{1 - \frac{2GM}{rc^2}} $$

Where:

- $\Delta t$ is the time interval measured far from the massive object (where the gravitational field is negligible).
- $\Delta t_0$ is the time interval as measured at a distance $r$ from the center of the massive object.
- $G$ is the gravitational constant.
- $M$ is the mass of the object.
- $r$ is the radial coordinate (which is analogous to the classical distance from the center of the object, but is actually a Schwarzschild coordinate).
- $c$ is the speed of light in a vacuum.

The combined formula under the [Schwarzchild metric](https://en.wikipedia.org/wiki/Schwarzschild_metric) (the charge, angular momentum, and cosmological constant are zero):

$$ \frac{dt_\text{E}}{dt_\text{c}} = \sqrt{ 1 - \frac{2GM}{rc^2} - \frac{v^2}{c^2} + \left( \frac{c^2}{2U} + 1 \right)^{-1} \frac{{v_\shortparallel}^2}{c^2} } $$

where:
- $v_\shortparallel$ is the radial velocity
