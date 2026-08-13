# Reading 002 — Chapter 1, §1.1: Complex Numbers and the Complex Plane

## Source

Elias M. Stein and Rami Shakarchi, *Complex Analysis*, Princeton Lectures in Analysis II.

## Scope

Chapter 1, §1.1, “Basic properties,” only. This record continues the joint reading from the Foreword and Introduction.

## Opening frame

Chapter 1 opens with Borel's observation that the sweeping development of modern mathematics owes much to complex numbers, despite their origin in the apparently absurd idea of numbers whose squares are negative.

Stein and Shakarchi begin concretely. A complex number is written

`z = x + iy`,

with `x,y ∈ R` and `i^2 = -1`. The real and imaginary parts are

`Re(z) = x`, `Im(z) = y`.

The key representation is geometric: `z = x + iy` is identified with the point `(x,y)` in `R^2`. Thus the complex numbers form a plane, with the real axis and the imaginary axis as coordinate axes.

## Addition and multiplication

Addition behaves exactly like vector addition in the plane:

`(x1 + iy1) + (x2 + iy2) = (x1+x2) + i(y1+y2)`.

Multiplication is different and more revealing:

`(x1 + iy1)(x2 + iy2) = (x1x2-y1y2) + i(x1y2+y1x2)`.

The usual algebraic laws—commutativity, associativity, distributivity—remain intact.

The important geometric distinction is that multiplication is not merely another coordinatewise operation. Multiplication by `i` rotates a point by `π/2`. More generally, once polar form is introduced, multiplication will be seen as a rotation composed with a dilation.

## Modulus

The modulus of `z = x+iy` is

`|z| = (x^2+y^2)^(1/2)`.

This is exactly Euclidean distance from the origin. Consequently, the ordinary geometry of `R^2` enters directly into the algebra of `C`.

The triangle inequality becomes

`|z+w| ≤ |z|+|w|`.

Other useful consequences include

`|Re(z)| ≤ |z|`,

`|Im(z)| ≤ |z|`,

and

`||z|-|w|| ≤ |z-w|`.

The last inequality says that the difference between the magnitudes of two complex numbers cannot exceed the distance between the numbers themselves.

## Conjugation

For `z=x+iy`, the conjugate is

`bar(z)=x-iy`.

Geometrically this is reflection across the real axis.

The real and imaginary parts can be recovered algebraically from `z` and its conjugate:

`Re(z)=(z+bar(z))/2`,

`Im(z)=(z-bar(z))/(2i)`.

A particularly important identity is

`|z|^2 = z bar(z)`.

For `z ≠ 0`, this gives

`1/z = bar(z)/|z|^2`.

Thus conjugation links geometry (length) to algebra (multiplicative inverse).

## Polar form

Every nonzero complex number may be written

`z = r e^(iθ)`

with `r=|z|>0` and

`e^(iθ)=cos θ+i sin θ`.

The argument `θ` is the angle from the positive real axis, determined up to multiples of `2π`.

If

`z = r e^(iθ)` and `w = s e^(iφ)`,

then

`zw = rs e^(i(θ+φ))`.

This is the central geometric meaning of complex multiplication:

- magnitudes multiply;
- angles add.

Equivalently, multiplication by a nonzero complex number performs a dilation by its modulus and a rotation by its argument.

## Joint understanding

The authors are not merely adding an imaginary coordinate to real arithmetic. They construct one object in which algebra and planar geometry interact tightly:

- addition corresponds to vector addition;
- modulus corresponds to Euclidean length;
- conjugation corresponds to reflection;
- multiplication corresponds to rotation plus dilation;
- inversion combines conjugation with reciprocal scaling.

This matters for the question left open in Reading 001. A complex increment `h` does not merely vary in size; it has both magnitude and direction. Requiring the complex difference quotient to approach one value as `h→0` therefore asks for compatibility across every direction encoded by the complex plane. We have not yet proved the strength of this condition; that comes when the book reaches holomorphic functions and the Cauchy-Riemann equations.

## Provisional interpretive observation

Complex notation does more than compress two real coordinates. It equips the plane with an algebra whose multiplication already carries geometric action. The same object can therefore be read algebraically and geometrically without translating into separate systems.

This is a study observation only. No architectural or ministerial consequence is adopted from it.

## Next reading

Chapter 1, §1.2–§1.3:

- convergence and Cauchy sequences;
- completeness of `C`;
- open and closed sets;
- compactness;
- connectedness and regions.

These sections supply the topological setting in which holomorphic functions will later live.
