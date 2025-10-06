Gaussian elimination, also known as Gaus-Jordan's method, is a method to solve [[Linear algebra|linear equations]] of any degree by representing the system as a [[Matrices|matrix]] to isolate a variable and get the others. For instance, consider the following linear equation.

$$
\begin{cases}
4x+6y+z=-2 \\
5x-3y-z=8 \\
4x-2y+z=1
\end{cases}
$$

This system can be represented with matrices in the following way.

$$
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 1 & 1 & -2\\
5 & -3 & -1 & 8 \\
4 & -2 & 1 & 1
\end{array}
\end{pmatrix}
$$

This is called an extended matrix, since we are extending the original with the values after the equal sign. Gaussian elimination is kind of like a game to solve linear equations, in which we have the following rules.

- You can swap rows since this doesn't change the final result.
- You can multiply rows by any value that is not zero.
- You can add or subtract rows to other rows.
- You cannot multiply a row by zero.
- You cannot do anything non-linear, so squares, multiplying rows together, etc.
- Do column operations.
	- You can, but it gets messy to keep track of what you do, since column operations do change the variable itself.

The objective is to get a triangle of zeroes on either the top-right or bottom-left.

$$
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 1 & 1 & -2\\
\boxed0 & -3 & -1 & 8 \\
\boxed0 & \boxed0 & 1 & 1
\end{array}
\end{pmatrix}
\;\;\text{or}\;\;
\begin{pmatrix}
\begin{array}{ccc|c}
1 & \boxed0 & \boxed0 & -2\\
5 & -3 & \boxed0 & 8 \\
4 & -2 & 1 & 1
\end{array}
\end{pmatrix}
$$

>[!failure]
>If during the process of Gaussian elimination you get a 0 in the middle diagonal between those two possible triangles, it means the system is inconsistent and has no solutions (or infinite solutions).

# Example

Consider the following system of equations.

$$
\begin{cases}
2x+4y+6z=18 \\
4x+5y+6z=24 \\
3x+y-2z=4
\end{cases}
$$

We can represent this system as a matrix like so.

$$
\begin{pmatrix}
\begin{array}{ccc|c}
2 & 4 & 6 & 18\\
4 & 5 & 6 & 24 \\
3 & 1 & -2 & 4
\end{array}
\end{pmatrix}
$$

And now, we can start doing operations on the matrix. Remember the rules above, and you should be fine. Our goal is to get a triangle of zeroes.

$$
\begin{pmatrix}
\begin{array}{ccc|c}
2 & 4 & 6 & 18\\
4 & 5 & 6 & 24 \\
3 & 1 & -2 & 4
\end{array}
\end{pmatrix}
\xrightarrow{R_{1}\to \frac{1}{2}R_{1}}
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
4 & 5 & 6 & 24 \\
3 & 1 & -2 & 4
\end{array}
\end{pmatrix}
\xrightarrow{R_{2}\to R_{2} - 4R_{1}}
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
0 & -3 & -6 & -12 \\
3 & 1 & -2 & 4
\end{array}
\end{pmatrix}
$$
$$
\xrightarrow{R_{3}\to R_{3} - 3R_{1}}
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
0 & -3 & -6 & -12 \\
0 & -5 & -11 & -23
\end{array}
\end{pmatrix}
\xrightarrow{R_{2}\to -\frac{1}{3}R_{2}}
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
0 & 1 & 2 & 4 \\
0 & -5 & -11 & -23
\end{array}
\end{pmatrix}
\xrightarrow{R_{3}\to R_{3}+5R_{2}}
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
0 & 1 & 2 & 4 \\
0 & 0 & -1 & -3
\end{array}
\end{pmatrix}
$$

Look at that! We have a triangle of zeroes.

$$
\begin{pmatrix}
\begin{array}{ccc|c}
1 & 2 & 3 & 9\\
\boxed0 & 1 & 2 & 4 \\
\boxed0 & \boxed0 & -1 & -3
\end{array}
\end{pmatrix}
$$

If we translate this matrix back into a linear equation, we get the following.

$$
\begin{cases}
x+2y+3z=9 \\
y+2z=4 \\
-z=-3
\end{cases}
$$

Look at that! We have isolated $z$ in the bottom, and it's now a linear equation. Let's solve it.

$$
-z=-3
$$
$$
z=3
$$

Epic. Now, we can substitute that in the equation that only has $y$ and $z$ in it.

$$
y+2z=4
$$
$$
y+2(3)=4
$$
$$
y+6=4
$$
$$
y=-2
$$

Fantastic. Now, let's substitute for both in the last equation.

$$
x+2y+3z=9
$$
$$
x+2(-2)+3(3)=9
$$
$$
x-4+9=9
$$
$$
x+5=9
$$
$$
x=4
$$

And there we have it. We have used Gaussian elimination to find all three unknowns.

>[!success]
>As you saw, this technique is shorter than [[Cramer's rule]] or simple [[Substitution|substitution]]. It is the go-to method for 3x3 matrices.