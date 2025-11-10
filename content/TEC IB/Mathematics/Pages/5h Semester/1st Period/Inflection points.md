Inflection points in a [[Function|function]] are points where the curve's [[Concavity|concavity]] changes. Additionally, an inflection point is called a critical point of inflexion when the value obtained through the second derivative when plugged into the first derivative equals zero.

![[point of inflection.png|center|400]]

# Second derivative test

The second derivative test is a way to get the points of inflection of a function. It involves [[Derivative|differentiating]] a function twice. The second derivative is essentially the derivative of the derivative. Then, you get the zeroes.

## Example

Consider the following function and its graph.

$$
f(x)=x^{3}
$$

![[point of inflection fun.png|center|400]]

At a simple sight, it is easy to see that the concavity changes at some point during the middle. We should get this point analytically.

First, we differentiate the function twice.

$$
\frac{d}{dx}[x^{3}]=3x^{2}
$$
$$
\frac{d^{2}}{dx^{2}}[x{^3}]=6x
$$

Pretty simple. Now we equal this to zero.

$$
6x=0
$$
$$
x=0
$$

Again, pretty simple. Now we know that this function has a change of concavity, we should check what that change is. We can put this number on our number line.

![[number line extrema.png|center|500]]

We know that in any point in the function other than there the function is concave up or down. We can plug in values from $-\infty$ to 0 and from 0 to $\infty$ in the second derivative to see whether the function is concave up or down at those points. Let's do that.

- $f''(-1)=6(-1)=-6$. Concave down.
- $f''(1)=6(1)=6$. Concave up.

This example is very obvious, but you get the point.

![[completed number line extrema.png|center|500]]

The interval where the function is concave down is $(-\infty,0)$, and it is concave up in $(0,\infty)$. Now we should get the coordinates of 0 in the function by plugging it into the original function.

$$
f(0)=(0)^{3}
$$
$$
f(0)=0
$$

We now know that $(0,0)$ is a point of inflection for this function. To know whether it is a stationary point of inflection, we should plug it in the first derivative and see what happens.

$$
f'(0)=3(0){^2}
$$
$$
f'(0)=0
$$

It is! So, there we have it. This function has one stationary point of inflection: $(0,0)$.