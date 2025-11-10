Extrema in [[Calculus|calculus]] are extreme points of a [[Function|function]]'s curve. There are two types:

- **Minimum**: A point that seems to be lower in the curve. A valley.
- **Maximum**: A point that seems to be higher in the curve. A peak.

Extrema can be local or global. Local means that it is compared to the nearby area of the curve, while global means that it is the biggest or smallest value in the function in general.

![[max and mins.png|center|400]]

>[!important]
>Extrema are also called turning points since they are points where a function starts to increase or decrease.

# First derivative test

The first derivative test is a way to get the extrema (or turning points) of a function. This test consists of [[Derivative|differentiating]] a function once, and then getting its zeroes. The turning points once we know the increasing or decreasing parts of a function can be interpreted like so:

- If it's increasing and then decreases, it is a maximum.
- If it's decreasing and then increases, it is a minimum.

## Example

Consider the following function and its graph.

$$
f(x)=x^{2}-2
$$

![[example graph for extrema.png|center|400]]

At a simple sight, it is easy to see the only extrema of this function. It is $(-2,0)$, since that is the point where the parabola blooms. However, we can also do this analytically with the first derivative test.

First, we differentiate the function

$$
\frac{d}{dx}[x^{2}-2]=2x
$$

Pretty simple. Now we equal this to zero.

$$
2x=0
$$
$$
x=0
$$

Again, pretty simple. Now we know that this function has an extrema at this point. But, we don't know what this extrema is. We can put it in our number line though.

![[number line extrema.png|center|500]]

Now, we know that in any point in the function other than there the function is increasing or decreasing. It's not doing either at that point since the [[Tangent (calculus)|tangent]]'s [[Slope|slope]] is 0, and when a slope is zero it means that it is a straight line. 

We can plug in values from $-\infty$ to 0 and from 0 to $\infty$ in the first derivative to see whether the function is increasing or decreasing at those points. Let's do that.

- $f'(-1)=2(-1)=-2$. Decreasing.
- $f'(1)=2(1)=2$. Increasing.

This example is very obvious, but you get the point. 

![[completed number line extrema.png|center|500]]

The interval where the function is decreasing is $(-\infty,0)$, and it is increasing in $(0,\infty)$. Since the function decreases and then increases after 0, we know that 0 is a minimum.

To get the actual coordinates of 0, we just plug 0 into the original function.

$$
f(0)=(0)^{2}-2
$$
$$
f(0)=-2
$$

So there we have it. This function only has one extrema: a global minimum at the point $(0,-2)$.

>[!warning]
>Determining whether extrema are global or local in IB can only be done with pure logic or by looking at the graph. Know your functions!