A definite integral is a type of [[Integral|integral]] that gives you a number as a result, which is the area under the curve within an interval of a function. A definite integral looks something like this.

$$
\int_{a}^{b} f(x) \, dx
$$

>[!note]
>The area under the curve refers to the area between the curve and the x-axis.

# Properties

There are some properties of the definite integral that allow you to solve it right away if you are given the result of certain other integrals by just manipulating your values. You should know them to make your life easier!

$$
\int_{a}^{a} f(x) \, dx=0 
$$
$$
\int_{a}^{b} f(x) \, dx=-\int_{b}^{a} f(x) \, dx 
$$
$$
\int_{a}^{b} f(x) \, dx =\int_{a}^{c} f(x) \, dx +\int_{c}^{b} f(x) \, dx ,\;\text{when }\;a<c<b
$$

## Negative areas

Obviously areas can never be negative. There is no such thing in the real world. However, in mathematics, when a curve passes underneath the x-axis, if you get the integral of that it will be negative. So, if you want the 'net' area of something, you should use the absolute value.

![[positive and negative areas.png|center|400]]

# Example

For instance, consider the following function.

$$
f(x)=-\frac{1}{2}x+3
$$

Say we want to get the area under the curve of this function between the intervals of 1 to 4, as seen below.

![[area under curve.png|center|400]]

We do this by getting the definite integral.

$$
\int_{1}^{4} -\frac{1}{2}x+3 \, dx=\frac{21}{4}u^{2} 
$$

# Sharp curves

Sometimes we have curves that are very sharp and have multiple edges, almost like someone had drawn them with a pencil. For instance, consider the following curve below.

![[sharp curve.png|center|400]]

If we want to get the area under the curve, we could notice that this curve is made out of multiple functions. For instance, consider the line from point $(2,3)$ to point $(4,-3)$. We could use the formula for the [[Slope|slope]] to get this function's slope

$$
m=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}
$$
$$
m=\frac{-3-3}{4-2}
$$
$$
m=-\frac{6}{2}=-3
$$

With the slope and taking in mind the two points we labeled as $x_{1}$ and $y_{1}$, we can use the formula for getting function with the slope and a point.

$$
y-y_{1}=m(x-x_{1})
$$
$$
y-3=-3(x-2)
$$
$$
y-3=-3x+6
$$
$$
y=-3x+6+3
$$
$$
y=-3x+9
$$

Now we have a function for this line segment! We can do the same process for all lines, and we get the functions as seen below.

![[sharp functions labeled.png|center|400]]

Therefore, the area of these function's curves corresponds to the following integral.

$$
\int_{0}^{2} 3 \, dx+\int_{2}^{4} -3x+9 \, dx +\int_{4}^{7} 3x-15 \, dx  =\frac{21}{2}u^{2}
$$

# Fundamental theorem of calculus

![[Fundamental theorem of calculus]]

# Area between curves

If two functions intercept and there is an area between those two function's curves, you can get that area by doing some tinkering. If two functions, $y_{1}$ and $y_{2}$ are continuous, which is to say that their graphs have no gaps or breaks, we can get the area between those curves with an integral.

The equation is always the integral of the function above minus the integral of the function below.

$$
\int_{a}^{b} y_{1} \, dx-\int_{a}^{b} y_{2} \, dx=\text{Area}  
$$

## Example

Consider the curves below.

![[area between curves.png|center|400]]

These curves are formed by the following functions, as seen below.

$$
f(x)-x^{2}+5
$$
$$
g(x)=x+3
$$

In order to know the points where these two intersect, we equal the functions to each other and solve, as seen below.

$$
-x^{2}+5=x+3
$$
$$
-x^{2}+5-x=3
$$
$$
-x^{2}-x+5-3=0
$$
$$
-x^{2}-x+2=0
$$

Solving the equation we get that $x_{1}=-2$ and $x_{2}=1$. Those are our boundaries for our integral.

Now, we can see from the graph pretty easily that $f(x)$ is above $g(x)$. However, sometimes it is hard to tell. To know which function is on top and on the bottom, you can evaluate both functions some value in between that interval. Let's do 0.

- $f(0)=-(0)^{2}+5=5$
- $g(0)=(0)+3=3$

Since the bigger value is $f(0)$, then that means that $f(x)$ is above $g(x)$ in this interval. So, now we just write down our integral and solve it.

$$
\int_{-2}^{1} f(x) \, dx-\int_{-2}^{1} g(x) \, dx = 4.5u^{2}
$$
