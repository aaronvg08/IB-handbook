A plane is like an infinite sheet of paper in 3D space. If a function int he form of $ax+bx+c=0$, [[General form|general form]], then a function in the following form creates a plane.

$$
ax+by+cz=0
$$

# Creating a plane

To create a plane, you need three points in space. Consider the following points, $A,B$, and $C$.

$$
A=(-1,-4,4)
$$
$$
B=(4,5,0)
$$
$$
C=(-6,3,2)
$$

![[three 3d points.png|center|400]]


To create a plane out of these points, we have to choose a point of origin. For this example, let's pick $A$. We create two vectors that stem from $A$ and into the other two points, like so.

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

Next, we need to get the [[Cross product|cross product]] of these two vectors. It will yield some value. It isn't important, but it should look like this.

$$
\vec{n}=\vec{V}_{AB}\times \vec{V}_{AC}
$$
$$
\vec{n}=(A,B,C)
$$

Next, we plug these values into the following formula.

$$
A(x-x_{0})+B(y-y_{0})+C(z-z_{0})
$$

Where $x_{0},y_{0}$, and $z_{0}$ are the coordinates of the point where the vectors stemmed from. In this case, $A$. If we do, we get a plane, like seen below.

![[plane out of two vectors.png|center|400]]

# Intersection

The intersection of planes depends on how many are intersecting. We can generalize that each time we add a plane that intersects, we reduce the dimension of the result.

>[!question]
>By this it means we go from a 3D plane, to a line, to a dot. 3D, to 2D, to 1D.

The intersection between two planes is a line, as long as the planes aren't parallel. It can even be seen as an equation in the [[Point-slope form|point-slope form]] or the [[General form|general form]]. An example can be seen below.

![[intersection between two planes.png|center|400]]

The intersection between three planes is a dot. This dot can even be seen as the solution of a 3x3 [[Linear algebra|system of equations]]. There are multiple cases for this, depending on the 'slope' of the planes, as seen below.

![[plane solutions.png|center|650]]

>[!important]
>Do note that there is no such thing as a 'slope' when it comes to planes, unfortunately.