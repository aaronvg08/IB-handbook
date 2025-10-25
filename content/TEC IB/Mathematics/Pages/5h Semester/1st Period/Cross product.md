The cross product, also known as the vectorial product, is a way to take two different vectors and create a new vector that is perpendicular to both. 

To calculate it, you have to take the determinant of a 3x3 matrix made out of the $x,y,$ and $z$ point.

$$
\vec{A}=
\begin{pmatrix}
x_{1} \\
y_{1} \\
z_{1}
\end{pmatrix}
$$
$$
\vec{B}=
\begin{pmatrix}
x_{2} \\
y_{2} \\
z_{3}
\end{pmatrix}
$$
$$
\vec{A}\times \vec{B}=
\begin{vmatrix}
x & y & z \\
x_{1} & y_{1} & z_{1} \\
x_{2} & y_{2} & z_{2}
\end{vmatrix}
$$

# Geometric interpretation

The cross product, as seen in the definition, creates a vector that is parallel to both. However, this can also be seen as a vector that is parallel to the plane that two vectors create.

Consider the following vectors, $\vec{V}_{AB}$ and $\vec{V}_{AC}$.

$$
\vec{V}_{AB}=\begin{pmatrix}
5 \\
9 \\
-4
\end{pmatrix}
$$
$$
\vec{V}_{AC}=\begin{pmatrix}
-5 \\
7 \\
-2
\end{pmatrix}
$$

![[two vectors.png|center|400]]


You can create a [[Plane|plane]] out of these vectors.

![[plane out of two vectors.png|center|400]]

The cross product of these vectors can be obtained with the following procedure.

$$
\vec{V}_{AB}\times \vec{V}_{AC}=
\begin{vmatrix}
x & y & z \\
5 & 9 & -4 \\
-5 & 7 & -2
\end{vmatrix}
$$
$$
=
\begin{vmatrix}
9 & -4 \\
7 & -2
\end{vmatrix}
x
-
\begin{vmatrix}
5 & -4 \\
-5 & -2
\end{vmatrix}
y
+
\begin{vmatrix}
5 & 9 \\
-5 & 7
\end{vmatrix}
z
$$
$$
=((-18)-(-28))x-((-10)-(20))y+((135)-(-45))z
$$
$$
=10x+30y+80z
$$
$$
=
\begin{pmatrix}
10 \\
30 \\
80
\end{pmatrix}
$$

This is a vector! Now, this vector looks something like this.

![[cross product.png|center|400]]

It looks like an additional vector 'stabbing' the plane, entirely perpendicular.

