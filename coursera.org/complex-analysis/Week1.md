# Week 1: Introduction to Complex Numbers

## Lesson 1 History of complex numbers

- Important people: Riemann, Cauchy, Weierstrass
- Complex dynamics: Mandelbrot set, Julia sets
- Complex functions: continuity, complex differentiation
- Conformal mapping: Mobius transformations and the Riemann mapping theorem
- Complex integration: Cauchy theory and consequences
    - Prove the Fundamental Theorem of Algebra
- Power series representation of analytic functions
    - Riemann hypothesis - prime numbers

### Brief history of complex numbers

- Solutions for a quadratic equation:
$$ x^2 = mx + b $$
$$ x = \frac{m}{2} \pm \sqrt{\frac{m^2}{4} + b} $$
- Cubic equations were the real reason for having complex numbers 
    - Del Fero and Tartaglia gave an analytic solution for the cubic equation: $x^3 = px + q$
        $$ x = \sqrt[3]{\sqrt{\frac{q^2}{4} - \frac{p^3}{27}} + \frac{q}{2}} - \sqrt[3]{\sqrt{\frac{q^2}{4} - \frac{p^3}{27}} - \frac{q}{2}}$$
- Bombelli's Problem (the birth of complex analysis): for $x^3 = 15x + 4$ we have $x = \sqrt[3]{2 + \sqrt{-121}} + \sqrt[3]{2 - \sqrt{-121}}$ and we can replace $\sqrt[3]{2 + \sqrt{-121}}$ with $2 + \sqrt{-1}$ and $\sqrt[3]{2 - \sqrt{-121}}$ with $2 - \sqrt{-1}$, which add up to $4$

## Lesson 2 Algebra and geometry in the complex plane

- Complex numbers are expressions of the form $z = x + iy$
    - $x$ is the real part
    - $y$ is the imaginary part
    - the set of complex numbers: $\mathbb{C}$ (the complex plane)
    - real numbers $\mathbb{R}$ are a subset of $\mathbb{C}$
    - the complex plane can be identified with $\mathbb{R}^2$

- Modulus: $|z| = \sqrt{x^2+y^2}$

- Multiplication: $(x + iy)(u + iv) = (xu - yv) + i(xv + yu)$
    - properties: associative, commutative, distributive

- Division: $z = x + iy$ and $w = u + iv$
    $$ \frac{z}{w} = \frac{(x + iy)(u - iv)}{(u + iv)(u - iv)} = \frac{xu + yv}{u^2 + v^2} + i \frac{yu + xv}{u^2 + v^2} $$

- Complex conjugate of $z = x + iy$ is $\overline{z} = x - iy$
    $$ \frac{1}{z} = \frac{\overline{z}}{z \overline{z}} = \frac{\overline{z}}{|z|^2} $$
    $$ Re(z) = \frac{z + \overline{z}}{2} $$
    $$ Im(z) = \frac{z - \overline{z}}{2i} $$

- Inequalities:
    - $-|z| \leq Re(z) \leq |z|$
    - $-|z| \leq Im(z) \leq |z|$
    - $|z + w| \leq |z| + |w|$ (triangle inequality)
    - $|z - w| \geq |z| - |w|$ (reverse triangle inequality)

- Fundamental Theorem of Algebra: A polynomial of degree $n$ has $n$ roots

## Lesson 3 Polar representation of complex numbers

- Polar coordinates: $z = x + iy$, $z \neq 0$ can be described by the distance from the origin $r = |z|$ and the angle $\theta$ between the positive x-axis and the line segment from $0$ to $z$
    - $x = r\ cos\theta$
    - $y = r\ sin\theta$
    - polar representation: $z = r (cos\theta + i\ sin\theta)$
    - $\theta$ is not unique!

- Principal argument: $Arg(z)$ is the value $\theta \in (-\pi, \pi]$
    - $arg(z) = \theta + 2k\pi, k \in \mathbb{Z}$

- Exponential notation: $e^{i\theta}=cos\theta + i\ sin\theta$

- Polar form: $z = re^{i\theta}$
    - $e^{i\theta} = e^{i(\theta + 2k\pi)}, k \in \mathbb{Z}$

- Properties of the polar form:
    - $|e^{i\theta}| = 1$
    - $\overline{e^{i\theta}} = e^{-i\theta}$
    - $\frac{1}{\overline{e^{i\theta}}} = e^{-i\theta}$
    - $e^{i(\theta + \phi)} = e^{i\theta} e^{i\phi}$

- Conclusions for the $arg$ function:
    - $arg(\overline{z}) = -arg(z)$
    - $arg(\frac{1}{z}) = -arg(z)$
    - $arg(z_1 z_2) = arg(z_1) + arg(z_2)$
        - note that $Arg((-1)(-1)) \neq Arg(-1) + Arg(-1)$

- De Moivre's Formula
    - $(e^{i\theta})^n = e^{i\ n\theta}$
    - $(cos\theta + i\ sin\theta)^n = cos(n\theta) + i\ sin(n\theta)$
    - used to derive properties for $sin$ and $cos$
    $$ cos(3\theta) = cos^3\theta - 3 cos\theta\ sin^2\theta $$
    $$ sin(3\theta) = 3cos^2\theta\ sin\theta - sin^3\theta $$


## Lesson 4

## Lesson 5