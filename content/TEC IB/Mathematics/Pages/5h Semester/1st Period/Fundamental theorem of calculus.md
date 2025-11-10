The fundamental theorem of calculus is not how [[Calculus|calculus]] started, but it does show us how to solve [[Definite integral|definite integrals]] without the calculator. It states that, as long as you know an antiderivative of a function, you can get its definite integral like so.

$$
\int_{a}^{b} f(x) \, dx=F(b)-F(a) 
$$

Where $F(x)$ is an antiderivative of $f(x)$.

>[!question] What about $C$?
>When doing this, $C$ gets cancelled since it would just be $C-C$ anyways.

# Example

We want to solve the following definite integral.

$$
\int_{1}^{4} -\frac{1}{2}x+3 \, dx
$$

First, let's get the antiderivative of this function. Aka, the [[Indefinite integral|indefinite integral]].

$$
\int -\frac{1}{2}x+3 \, dx=-\frac{\frac{1}{2}x^{2}}{2} + 3x+C
$$
$$
\int -\frac{1}{2}x+3 \, dx=-\frac{x^{2}}{4} + 3x+C
$$

We evaluate this from 1 to 2. We indicate this like so.

$$
\left.-\frac{x^{2}}{4} + 3x \right\vert^{4}_{1}
$$

And then we do it.

$$
\left(-\frac{4^{2}}{4}+3(4)\right)-\left(-\frac{1^{2}}{4}+3(1)\right)
$$
$$
\left(-\frac{16}{4}+12\right)-\left(-\frac{1}{4}+3\right)
$$
$$
\left(-4+12\right)-\left(\frac{11}{4}\right)
$$
$$
8-\frac{11}{4}
$$
$$
\frac{21}{4}
$$

So there we have it. The area of this section under the curve is $\frac{21}{4}$.