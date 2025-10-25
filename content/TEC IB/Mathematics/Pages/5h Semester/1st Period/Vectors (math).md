Vectors in math are mathematical objects that have magnitude and an angle. They represent a specific line in space, and can sometimes represent other things, such as shapes or planes.

# Creating

Let's imagine we have a 3D space. We can have multiple points, such as the following.

$$
A=(-1,-4,4)
$$
$$
B=(4,5,0)
$$

![[points on 3d plane.png|center|400]]

If we draw a line across from point A to point B, then, we have a vector.

![[vector on 3d plane.png|center|400]]

This is a vector! It can represented with a [[Matrices|matrix]], like so.

$$
\vec{V}_{AB}=\begin{pmatrix}
5 \\
9 \\
-4
\end{pmatrix}
$$

It represents the operation of $B-A$, even thought the vector goes from $A$ to $B$. We always go from tail to peak when creating a vector. Therefore, the vector $\vec{V}_{BA}$ is like so.

$$
\vec{V}_{BA}=
\begin{pmatrix}
-1-4 \\
-4-5 \\
4-0
\end{pmatrix}
$$
$$
\vec{V}_{BA}=
\begin{pmatrix}
-5 \\
-9 \\
4
\end{pmatrix}
$$

Each of this can also be represented as how many steps you take to get there from the $x,y,$ and $z$ axis. This is why we subtract to get the overall vector.

$$
\vec{V}_{AB}=5i-2j+5k
$$
$$
\vec{V}_{BA}=-5i-9j+4k
$$

>[!note]
>We can express $x,y,$ and $z$ axis using the letters $i$, $j$, and $k$ instead.

We can interpret each of this values differently, whether they are positive or negative.

$$
\vec{V}=
\overbrace{ \begin{pmatrix}
a\;\}\;\text{left or right} \\
b\;\}\;\text{down or up} \\
c\;\}\;\text{back or front}
\end{pmatrix} }^{-\;\;+ }
$$

# Magnitude

![[Magnitude (vectors)]]

# Operations
## Multiplication

When you multiply a [[Vectors (math)|vector]], you are changing its magnitude in some way. There are two ways you can multiply a vector, by a scalar, or by another vector. Though these are normally called the [[Scalar product|scalar]] and [[Vectorial product|vectorial]] products.

Multiplying a vector by a scalar $k$ changes its magnitude. In the same direction if $k>0$, or in the opposite if $k<0$.

$$
k v=
\begin{pmatrix}
k\cdot v_{1} \\
k\cdot v_{2} \\
k\cdot v_{3}
\end{pmatrix}
$$

>[!Important]
>This also means that multiplying a vector by $-1$ simply changes it to the opposite direction!

An important note is that two non-zero vectors are parallel if one of them is a scalar multiple of the other. For instance, consider the following vectors, $a$ and $b$.

$$
a=
\begin{pmatrix}
4 \\
3 \\
1
\end{pmatrix}
$$
$$
b=
\begin{pmatrix}
8 \\
6 \\
2
\end{pmatrix}
$$

These vectors are parallel because $2a=b$.

## Dot product

![[Dot product]]

## Cross product

![[Cross product]]

# Planes

![[Plane]]