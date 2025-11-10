A limit in [[Calculus|calculus]] is the way we describe the output of a [[Function|function]] as the input gets closer and closer (approaches) a certain value. Limits are usually written down with the following notation.

$$
\lim_{ x \to 0 } \frac{1}{x}
$$

A limit can exist or it cannot exist. When it does exist, the limit is always a numerical value.

# Evaluating

## The limit exists

The meaning of the limit can be thought of as walking ants on a curve. Consider the following function and its curve, as seen below.

$$
f(x)=\cos (x)
$$


![[sine example.png|center|400]]

We can evaluate functions at any value we want as long as it is a real number. Let's pick zero. So, we can say that we are getting the limit as $x$ approaches 0, which is written as seen below.

$$
\lim_{ x \to 0 } \cos (x)
$$

When $x$ approaches this value, it approaches both from negative infinity ($-\infty$) and from positive infinity ($\infty$). Let's try approaching from negative infinity first. This is written like below.

$$
\lim_{ x \to 0^{-}}\cos(x)
$$

We imagine ants walking from the curve towards the value we are aiming for, which in this case is zero. They walk, walk, walk, getting closer and closer to our value.

![[ants from left cosine.png|center|400]]

Eventually they do get there. When they do, they reach the value when $x=0$. So, we can evaluate our function.

$$
\lim_{ x \to 0^{-} }\cos (x)=\cos(0) 
$$
$$
\cos(0)=1
$$

Therefore, the limit as we approach from the left is 1. Next, we do the limit approaching from positive infinity. This is written down like so.

$$
\lim_{ x \to 0^{+} } \cos(x)
$$

Here, the ants are coming from the right since that is where positive infinity is at. They get closer, and closer, and closer to the value.

![[ants from right cosine.png|center|400]]

Eventually they do get there. When they do, they reach the value when $x=0$. So, we can evaluate our function.

$$
\lim_{ x \to 0^{+} }\cos (x)=\cos(0) 
$$
$$
\cos(0)=1
$$

As we can see, the limit from both sides is the same value. Therefore, the limit exists! The overall limit of this function is 1.

$$
\lim_{ x \to 0 } \cos (x)=1
$$

>[!note]
>A limit exists if the ants from both sides eventually meet. 

>[!important]
>Sometimes, some functions cannot be evaluated since we run into indeterminations. However, if the ants still meet at a point, the limit exists and is a real value.

## The limit doesn't exist

Consider the following function.

$$
f(x)=\frac{1}{x}
$$

As you can see, it is a rational function. Therefore, its graph will look something like this.

![[rational example.png|center|400]]

We get the limit from negative infinity first. So, we write it down and imagine our ants.

$$
\lim_{ x \to 0^{-} } \frac{1}{x}
$$

![[ants from left rational.png|center|400]]

Because of the [[Asymptote|asymptote]], the ants will walk down, down, down, and forever down. They will end up in negative infinity. Therefore, that is our limit when approaching from the left.

$$
\lim_{ x \to 0^{-} } \frac{1}{x}=-\infty 
$$

Now, we should approach from the right. We write it down and imagine our ants.

$$
\lim_{ x \to 0^{+} } \frac{1}{x}
$$

![[ants from right rational.png|center|400]]

Again, because of the asymptote, the ants will walk up, up, up, and forever up. They will end up in positive infinity. Therefore, that is our limit when approaching from the right.

$$
\lim_{ x \to 0^{+} } \frac{1}{x}=\infty
$$

As we can see, our limits when approaching from both sides are entirely different. We get infinity and negative infinity. Our ants will never meet since they will be in the other side of the world. Therefore, the limit does not exist.

$$
\lim_{ x \to 0 } \frac{1}{x}=\text{doesn't exist}
$$

# L'Hôpital's rule (HL)

