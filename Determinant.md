
Through out liner algebra vector is scaled using Scalar.

### 3d linear transformations
Second transformation * First transformation

### Determinant
the size that stretches squishes 
-ve used to show flip of matrix

det([a b.     = ad-bc
     c d])

det(M1M2) = det(M1)det(M2)

### Inverse matrices, column space, and null space

if determinant |A| = 0 you cannot inverse

you cannot squish line to plane
A x = v.

a*a- =1 called as identity
Similarly, for 3 equations and 3 unknowns, there will be no inverse if the corresponding transformation squishes 3D space onto a plane, onto a line, or onto a point. Those all correspond to a determinant of zero, since any region is squished onto a zero-volume region.
zero-determinant. When the output of a transformation is a line, meaning it is one-dimensional, we say the transformation has a rank of 1
If all the vectors land on some two-dimensional plane, we say the transformation has a rank of 2.
Null Space
Notice the zero vector will always be included in the column space since linear transformations must keep the origin fixed in place.

For a full-rank transformation, the only vector that lands at the origin is the zero vector itself. But for matrices that aren’t full rank, which squish to a smaller dimension, you can have a whole bunch of vectors land on zero. If a 2D transformation squishes space onto a line, there is a separate line in a different direction full of vectors that get squished on the origin.

Span of columns = column space\

If a 3D transformation squishes all of space onto a line, there is a whole plane full of vectors that land on the origin.

This set of vectors that land on the origin is called the “null space” or the “kernel” of your matrix. It’s the space of vectors that becomes null, in the sense that they land on the zero vector. In terms of the linear system of equations, if v→happens to be the zero vector, the null space gives you all possible solutions to the equation.


