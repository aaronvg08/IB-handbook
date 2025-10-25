Cramer's rule is a method for solving [[Linear algebra|systems of linear equations]] that consists in using the determinant of a system through [[Matrices|matrices]]. The way this method works is by calculating the system's determinant ($\Delta$) and then doing the following:

$$
\begin{matrix}
x=\frac{\Delta_{x}}{\Delta} & y=\frac{\Delta_{y}}{\Delta} & z=\frac{\Delta_{z}}{\Delta}
\end{matrix}
$$

You get the determinant of each variable, and then divide it by the whole system's determinant, depending on the number of unknowns.

The determinant is always acquired in the following way:

$$
\Delta=\overbrace{ \begin{vmatrix}
a_{1} & b_{1} \\
a_{2} & b_{2}
\end{vmatrix} }^{\begin{matrix}
x  & & y
\end{matrix} }=a_{1}b_{2}-b_{1}a_{2}
$$

>[!important]
>If the determinant is 0, then the system either has no solutions or infinitely many solutions. Getting the determinant of a system can help you prove if it has solutions or not.

And the determinant of a variable by excluding the variable's coefficients and adding the extra value at the end, like so.

$$
\begin{matrix}
\Delta_{x}=\overbrace{ \begin{vmatrix}
c_{1} & b_{1} \\
c_{2} & b_{2}
\end{vmatrix} }^{ \begin{matrix}
i &  & y
\end{matrix} }
=c_{1}b_{2}-b_{1}-c_{2}  & 
\Delta_{y}=\overbrace{ \begin{vmatrix}
a_{1} & c_{1} \\
a_{2} & c_{2}
\end{vmatrix} }^{ \begin{matrix}
x &  & i
\end{matrix} }
=a_{1}c_{2}-c_{1}a_{2}
\end{matrix}
$$

Both of these, where an equation looks like $a_{1}+b_{2}=c_{1}$. And by $i$, it means the $c$ values.

>[!note]
>This can be used for systems of 2x2 and 3x3, but it gets very lengthy and can cost you time. At least be assured that this is the method that the calculator uses.

# Example

## 2x2

Consider the following 2x2 system of equations.

$$
\begin{cases}
2x+5y=26 \\
5x-4y=-1
\end{cases}
$$

We get the [[Matrices#Determinant|determinant]] of the system like so.

$$
\Delta=\begin{vmatrix}
2 & 5 \\
5 & -4
\end{vmatrix}
$$
$$
\Delta=2(-4)-5(5)
$$
$$
\Delta=-8-25
$$
$$
\Delta=-33
$$

Then, we get the determinant of $x$.

$$
\Delta_{x}=\begin{vmatrix}
26 & 5 \\
-1 & -4
\end{vmatrix}
$$
$$
\Delta_{x}=26(-4)-5(-1)
$$
$$
\Delta_{x}=-104+5
$$
$$
\Delta_{x}=-99
$$

Then, we get the determinant of $y$.

$$
\Delta_{y}=\begin{vmatrix}
2 & 26 \\
5 & -1
\end{vmatrix}
$$
$$
\Delta_{y}=2(-1)-26(5)
$$
$$
\Delta_{y}=-2-130
$$
$$
\Delta_{y}=-132
$$

Now, we can get both variables! First, let's get $x$.

$$
x=\frac{\Delta_{x}}{\Delta}
$$
$$
x=\frac{-99}{-33}
$$
$$
x=3
$$

Now, let's get $y$.

$$
y=\frac{\Delta_{y}}{\Delta}
$$
$$
y=\frac{-132}{-33}
$$
$$
y=4
$$

And there we have both of our solutions!

## 3x3

Consider the following system of linear equations.

$$
\begin{cases}
2x+y-z=1 \\
3x+2y+2z=13 \\
4x-2y+3x=9
\end{cases}
$$

We can get the determinant by using the [[Determinant|3x3 determinant method]].

$$
\Delta=\begin{vmatrix}
2 & 1 & -1 \\
3 & 2 & 2 \\
4 & -2 & 3
\end{vmatrix}
$$
$$
\Delta=2
\begin{vmatrix}
2 & 2 \\
-2 & 3
\end{vmatrix}
-1
\begin{vmatrix}
3 & 2 \\
4 & 3
\end{vmatrix}
-1
\begin{vmatrix}
3 & 2 \\
4 & -2
\end{vmatrix}
$$
$$
\Delta=2[2(3)-2(-2)]-1[3(3)-2(4)]-1[3(-2)+2(4)]
$$
$$
\Delta=2(6+4)-1(9-8)-1(-6-8)
$$
$$
\Delta=2(10)-1(1)-1(-14)
$$
$$
\Delta=20-1+14
$$
$$
\Delta=33
$$

Now, we get the determinant of $x$ in the same way.

$$
\Delta_{x}=\begin{vmatrix}
1 & 1 & -1 \\
13 & 2 & 2 \\
9 & -2 & 3
\end{vmatrix}
$$
$$
\Delta_{x}=1
\begin{vmatrix}
2 & 2 \\
-2 & 3
\end{vmatrix}
-1
\begin{vmatrix}
13 & 2 \\
9 & 3
\end{vmatrix}
-1
\begin{vmatrix}
13 & 2 \\
9 & -2
\end{vmatrix}
$$
$$
\Delta_{x}=1[2(3)-2(-2)]-1[13(3)-2(9)]-1[13(-2)-2(9)]
$$
$$
\Delta_{x}=1(6+4)-1(39-18)-1(-26-18)
$$
$$
\Delta_{x}=1(10)-1(21)-1(-44)
$$
$$
\Delta_{x}=10-21+44
$$
$$
\Delta_{x}=33
$$

Next, we get the determinant of $y$.

$$
\Delta_{y}=
\begin{vmatrix}
2 & 1 & -1 \\
3 & 13 & 2 \\
4 & 9 & 3
\end{vmatrix}
$$
$$
\Delta_{y}=2
\begin{vmatrix}
13 & 2 \\
4 & 9
\end{vmatrix}
-1
\begin{vmatrix}
3 & 2 \\
4 & 3
\end{vmatrix}
-1
\begin{vmatrix}
3 & 13 \\
4 & 9
\end{vmatrix}
$$
$$
\Delta_{y}=2[13(9)-2(4)]-1[3(3)-2(4)]-1[3(9)-13(4)]
$$
$$
\Delta_{y}=2(39-18)-1(9-8)-1(27-52)
$$
$$
\Delta_{y}=2(21)-1(1)-1(-25)
$$
$$
\Delta_{y}=42-1+25
$$
$$
\Delta_{y}=66
$$

Now, the determinant of $z$.

$$
\Delta_{z}=
\begin{vmatrix}
2 & 1 & 1 \\
3 & 2 & 13 \\
4 & -2 & 9
\end{vmatrix}
$$
$$
\Delta_{z}=2
\begin{vmatrix}
2 & 13 \\
-2 & 9
\end{vmatrix}
-1
\begin{vmatrix}
3 & 13 \\
4 & 9
\end{vmatrix}
+1
\begin{vmatrix}
3 & 2 \\
4 & -2
\end{vmatrix}
$$
$$
\Delta_{z}=2[2(9)-13(-2)]-1[3(9)-13(4)]+1[3(-2)-2(4)]
$$
$$
\Delta_{z}=2(18-26)-1(27-52)+1(-6-8)
$$
$$
\Delta_{z}=2(44)-1(-25)+1(-14)
$$
$$
\Delta_{z}=88+25-14
$$
$$
\Delta_{z}=99
$$

Finally, we use all of these determinants to find the values of $x,y,\text{and}\;z$.

$$
x=\frac{\Delta_{x}}{\Delta}=\frac{33}{33}=1
$$
$$
y=\frac{\Delta_{y}}{\Delta}=\frac{66}{33}=2
$$
$$
z=\frac{\Delta_{z}}{\Delta}=\frac{99}{33}=3
$$

And there we have it. After all of this, we have the values of all of our unknowns.

>[!failure]
>As you saw, this gets very lengthy when it comes to 3x3 systems. It is recommended to use [[Gaussian elimination]] instead.
