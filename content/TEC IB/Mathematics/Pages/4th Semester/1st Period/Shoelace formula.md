The shoelace formula is a way to know the area of a [[Polygon|polygon]] if you know their coordinates on a cartesian grid. It works for all types of polygons, except for [[Circle|circles]], since circles have infinite points and aren't really joined by a straight line.

The shoelace formula is the following.

$$
A=\frac{1}{2} \left| \sum_{i=1}^{n} x_{i} (y_{i+1}-y_{i-1}) \right|
$$

# Example

The formula looks very complex, so here's an example of how to use it.

Consider the following polygon in the cartesian plane.

![[shoelace polygon.png|center|500]]

The coordinates of all the points are the following.

- **A**: $(1,6)$
- **B**: $(-4,3)$
- **C**: $(-5,-3)$
- **D**: $(3,1)$

We can write these coordinates in the following way with the formula. Be sure to write the numbers in a counter-clockwise way, starting with a specific point.

$$
A=\frac{1}{2} \left|
\begin{matrix}
\overbrace{ 1 }^{ A } & \overbrace{ -4 }^{ B } & \overbrace{ -5 }^{ C } & \overbrace{ 3 }^{ D } & \overbrace{ 1 }^{ A } \\
6 & 3 & -3 & -1 & 6
\end{matrix} \right| 
$$

Yes, we repeat the first one twice. Then, we do the shoelace method for multiplying these numbers. First, we multiply from up to down diagonally. So:

- $1\cdot 3 =3$
- $-4\cdot -3 =12$
- $-5\cdot -1 =5$
- $3\cdot 6 =18$

We annotate this numbers in the formula like so.

$$
A=\frac{1}{2}(3+12+5+18)
$$

But now we need to do from down to up diagonally. So:

- $6\cdot -4 =-24$
- $3\cdot -5 =-15$
- $-3\cdot 3 =-9$
- $-1\cdot 1 =-1$

And we add them to the formula subtracting.

$$
A=\frac{1}{2}[(3+12+5+18)-(-24+(-15)+(-9)+(-1)]
$$
$$
A=\frac{1}{2}[(3+12+5+18)-(-24-15-9-1)]
$$
$$
A=\frac{1}{2}[38-(-49)]
$$
$$
A=\frac{1}{2}(38+49)
$$
$$
A=\frac{1}{2}(87)
$$
$$
A=43.5 \; \text{units}^{2}
$$

And there we have it. The area of this polygon is 43.5 squared units.