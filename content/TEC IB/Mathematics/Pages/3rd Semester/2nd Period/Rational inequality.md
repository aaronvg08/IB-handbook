A rational inequality is an [[Inequalities|inequality]] that contains a [[Rational expression|rational expression]]. A rational equality may look something like this.

$$
\frac{3x^{2}-5}{x}>0
$$

# Solving

Solving a rational inequality is different than just finding $x$. 

## Step 1: Not equal to zero

You must first put everything on the left side and ensure the inequality is towards zero. For instance, consider the following inequality.

$$
\frac{4x^{2}}{2x-4}\geq -3
$$

Make sure everything is on the left side.

$$
\frac{4x^{2}}{2x-4}+3\geq 0
$$

You can turn $3$ into the denominator like you usually would with a normal fraction. For example:

$$
\frac{4}{5}+1
$$
$$
\frac{4}{5}+\frac{1(5)}{5}-\to \frac{4}{5} +\frac{5}{5}
$$

So, you do the following.

$$
\frac{4x^{2}}{2x-4}+\frac{3(2x-4)}{2x-4}=0
$$
$$
\frac{4x^{2}}{2x-4}+\frac{6x-12}{2x-4}=0
$$
$$
\frac{4x^{2}+6x-12}{2x-4}=0
$$

## Step 2: Get critical points

You need to analyze the inequality at its critical points. One of the critical points is the fact that the fraction's denominator cannot ever be zero, because as we know, you cannot divide by zero. So, you have to state that.

Our function is currently at this stage.

$$
\frac{4x^{2}+6x-12}{2x-4}=0
$$

We need to state that the denominator cannot be zero.

$$
2x-4 \neq 0
$$
$$
2x \neq 4
$$
$$
x \neq \frac{4}{2}
$$
$$
x \neq 2
$$

This is our first critical point.

Then, our second critical point is the numerator. We solve for $x$ in the numerator as above. We use the equal sign here even though it isn't equal, though. Trust, it will make sense at the end.

$$
4x^{2}+6x-12=0
$$

A quadratic! General formula to the rescue.

$$
x=\frac{-6\pm \sqrt{ 36-4(4)(-12) }}{8}
$$
$$
x=\frac{-6\pm \sqrt{ 228 }}{8}
$$
$$
x=\frac{-6\pm 2 \sqrt{ 57 }}{8}
$$

This is an ugly radical, but if we use the calculator, we get the following.

$$
\begin{matrix}
x_{1}=1.1374 \\
x_{2}=-2.637
\end{matrix}
$$

These are our two other critical points. Now, we have to analyze them.

## Step 3: Analyze critical points

We know the following.

$$
\begin{matrix}
x_{1}=1.1374 \\
x_{2}=-2.637 \\
x \neq 2
\end{matrix}
$$

We can chart these numbers on the number line.

![[critical points on num line.png|center|350]]

From the beginning of the problem, we know that the expression is greater than or equal to zero ($\geq$). Therefore, these intervals represent points where, in theory, the results should be greater than or equal to zero.

Therefore, we can pick numbers in between these intervals. Our [[Interval notation|intervals]] are the following:

- $(-\infty,-2.637)$.
- $(-2.637,0)$.
- $(0,1.1374)$.
- $(1.1374,2)$.
- $(2,\infty)$.

We pick a candidate number for each interval. So:

- $(-\infty,-2.637) \to-3$.
- $(-2.637,0)\to-1$.
- $(0,1.1374)\to 1$.
- $(1.1374,2)\to 1.5$.
- $(2,\infty) \to 5$.

Now, we evaluate the expression with a value for each interval and see what sign turns out. We can imagine the inequality as a function.

$$
f(x)=\frac{4x^{2}+6x-12}{2x-4}
$$
And so, we get the following results.

- $f(-3)=-0.6$. Negative.
- $f(-1)=2.333$. Positive.
- $f(1)=1$. Positive.
- $f(1.5)=-6$. Negative.
- $f(5)=19.666$. Positive.

We can be sure that when we pick any other number, we will get the same sign. Since we know that the inequality is greater than or equal to $0$, then we should only take the areas where the result is positive.

Since only in those areas the equation is positive, our result is the union of those intervals. So, this is our result.

$$
x\in[-2.637,1.1374]\cup(2,\infty)
$$

We include all number other than two, because $x$ can never be two, and we can't touch infinities. You can also represent this on the number line, which looks like this.

![[solution of rational on num line.png|center|350]]