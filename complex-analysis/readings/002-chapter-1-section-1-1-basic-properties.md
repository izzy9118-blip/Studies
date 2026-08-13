# Reading 002 — Chapter 1, §1.1: Basic Properties

## Source

Elias M. Stein and Rami Shakarchi, *Complex Analysis*, Princeton Lectures in Analysis II, Chapter 1, §1.1.

## Scope

This record covers the opening of Chapter 1 through the polar form of a complex number. It preserves the joint reading before moving to convergence and topology.

## Chapter 1's stated purpose

The authors describe Chapter 1 as preliminary material needed throughout the book. Its movement is:

1. algebraic and analytic properties of complex numbers;
2. topological notions in the complex plane;
3. holomorphicity and the Cauchy-Riemann equations;
4. power series;
5. curves and integration;
6. the first primitive/closed-curve result leading toward Cauchy's theorem.

The chapter therefore builds the language and geometry required before the central theorems can be proved.

## Complex numbers as numbers and points

A complex number has the form

`z = x + iy`, where `x,y ∈ R` and `i^2 = -1`.

The authors identify `z = x + iy` with the point `(x,y) ∈ R^2`. Thus the real part is the horizontal coordinate and the imaginary part is the vertical coordinate.

This is not merely a picture added after the algebra. The same object can be read algebraically as a number and geometrically as a point/vector in the plane.

## Addition

For

`z1 = x1 + iy1`, `z2 = x2 + iy2`,

addition is

`z1 + z2 = (x1+x2) + i(y1+y2)`.

Under the identification with `R^2`, this is ordinary vector addition.

## Multiplication

Multiplication is

`z1 z2 = (x1x2-y1y2) + i(x1y2+y1x2)`.

The authors emphasize that multiplication has a geometric meaning different from addition. Multiplying by `i` rotates a point by `π/2`. More generally, once polar form is introduced, multiplication becomes a rotation combined with a dilation.

This is a central shift in viewpoint: an algebraic operation can be interpreted as a geometric transformation.

## Absolute value and distance

For `z = x+iy`,

`|z| = (x^2+y^2)^(1/2)`.

This is exactly Euclidean distance from the origin. Consequently the triangle inequality in `C`,

`|z+w| ≤ |z|+|w|`,

is the familiar geometric triangle inequality.

The text also records

`|Re(z)| ≤ |z|`,

`|Im(z)| ≤ |z|`,

and

`||z|-|w|| ≤ |z-w|`.

The last inequality expresses that the difference between two distances from the origin cannot exceed the distance between the two points themselves.

## Complex conjugation

For `z=x+iy`, the conjugate is

`conj(z)=x-iy`.

Geometrically this is reflection across the real axis.

The text records the useful identities

`Re(z) = (z+conj(z))/2`,

`Im(z) = (z-conj(z))/(2i)`,

`|z|^2 = z conj(z)`,

and, for `z ≠ 0`,

`1/z = conj(z)/|z|^2`.

Again, algebra and geometry reinforce one another: reflection, distance, and inversion are linked through exact algebraic identities.

## Polar form

Every nonzero complex number can be written

`z = r e^(iθ)`,

where `r=|z|>0` and `θ` is an argument of `z`, determined modulo `2π`, with

`e^(iθ)=cos θ+i sin θ`.

If

`z = r e^(iθ)` and `w = s e^(iφ)`,

then

`zw = rs e^(i(θ+φ))`.

Thus multiplication separates into two simultaneous operations:

- magnitudes multiply: `r·s`;
- angles add: `θ+φ`.

This makes precise the authors' statement that multiplication by a complex number is a rotation composed with a dilation.

## Joint reading observation

The first important conceptual lesson of §1.1 is that complex numbers carry algebraic and geometric structure at once. The representation chosen is not cosmetic: Cartesian form makes addition and real/imaginary decomposition transparent; polar form makes multiplication transparent.

A recurring question for the study should therefore be: when a problem is difficult in one representation, does another representation expose the operative structure more directly?

This is a reading observation only, not yet an architectural rule for Sanctum or a certified analytical toolkit.

## Next reading

Chapter 1, §1.2 — Convergence, followed by §1.3 — Sets in the complex plane.
