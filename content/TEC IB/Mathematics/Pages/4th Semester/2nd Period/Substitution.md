Substitution is a method for solving [[Linear algebra|linear equations]] that consists in defining a variable in terms of the others and substituting for the rest.

>[!tip]
>It's best to use this for 3x3 max. It gets too cumbersome for systems with more than three unknowns.

# Example

Consider the following system of equations.

$$
\begin{cases}
4x+2y=14 \\
3x-5y=-22
\end{cases}
$$

Let's take the first equation.

$$
4x+2y=14
$$

You can define $x$ in terms of $y$. 

$$
4x=14-2y
$$
$$
x=\frac{14-2y}{4}
$$

Then, we substitute this definition into the other equation.

$$
3\left( \frac{14-2y}{4} \right)-5y=-22
$$

Then, we isolate $y$.

$$
\frac{3(14-2y)}{4}-5y=-22
$$
$$
\frac{42-6y}{4}-5y=-22
$$
$$
\frac{42-6y-20y}{4}=-22
$$
$$
\frac{42-26y}{4}=-22
$$
$$
42-26y=-88
$$
$$
-26y=-130
$$
$$
y=\frac{-130}{-26}
$$
$$
y=5
$$

We have found $y$! Now we can substitute the real value into the any of the two equations.

$$
4x+2(5)=14
$$
$$
4x+10=14
$$
$$
4x=4
$$
$$
x=\frac{4}{4}
$$
$$
x=1
$$

And now we have found $x$! We have found both values.