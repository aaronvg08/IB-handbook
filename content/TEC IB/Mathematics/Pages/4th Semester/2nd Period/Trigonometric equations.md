Trigonometric equations are equations that have [[Trigonometric ratios|trigonometric ratios]] on them. Most of the time, in order to solve trigonometric equations, you must employ multiple [[Trigonometric identities|identities]] and replace them in order to simplify the equation.

# Linear

Linear trigonometric equations are solved just like any other. Take the following equation for example.

$$
2\sin x=1\;\text{where:}-\pi\leq x\leq 3\pi
$$

You can just isolate $x$.

$$
\sin x=\frac{1}{2}
$$
$$
x=\arcsin\left( \frac{1}{2} \right)
$$
$$
x=\frac{\pi}{6}\;\text{rad}
$$

However, since trigonometric functions repeat infinitely, there are technically infinite solutions to trigonometric equations of [[Sine|sine]] and [[Cosine|cosine]]. You can state a general form like this.

$$
x=\frac{\pi}{6}\;\text{rad}+2\pi k
$$

However, the problem states that $-\pi\leq x\leq 3\pi$. So we must find all solutions in that interval. We can change $k$ to different value and see if it fits in the interval.

$$
x_{1}=\frac{\pi}{6}\;\text{rad}+2\pi(0)
$$
$$
x_{1}=\frac{\pi}{6}\;\text{rad}
$$

Since $\frac{\pi}{6}$ is within the interval, it is a valid solution. We go on with this for all values of $k$ we want:

- $k=-1$. $x=-\frac{11\pi}{6}$. Not in interval.
- $k=0$. $x=\frac{\pi}{6}$. In interval.
- $k=1$. $x=\frac{13\pi}{6}$. In interval.
- $k=2$. $x=\frac{25\pi}{6}$. Not in interval.

We stop at $k=2$. So, those are all of our solutions.

$$
\begin{matrix}
x_{1}=\frac{\pi}{6} \\
x_{2}=\frac{13\pi}{6}
\end{matrix}
$$

>[!note]
>Be sure to check each [[Trigonometric ratios|ratio]] page individually, because you do not add $2\pi$ for every function! It depends on the period of the ratio itself.

# Quadratic

Some trigonometric equations show up as if they were quadratics. For instance, consider the following equation.

$$
\sin ^{2}x-5\cos x+6=0
$$

You can solve this with the quadratic formula, if you replace $\sin x$ with $u$.

$$
u^{2}-5u+6=0
$$

Solve with the quadratic formula.

$$
u=\frac{5\pm \sqrt{ 25-4(1)(6) }}{2(1)}
$$
$$
u=\frac{5\pm \sqrt{ 25-24 }}{2}
$$
$$
u=\frac{5\pm \sqrt{ 1 }}{2}
$$
$$
\begin{matrix}
u_{1}=\frac{5+1}{2}=\frac{6}{2}=3 \\
u_{2}=\frac{5-1}{2}=\frac{4}{2}=2
\end{matrix}
$$

So, we have two possible solutions. This means that we have two possible general forms.