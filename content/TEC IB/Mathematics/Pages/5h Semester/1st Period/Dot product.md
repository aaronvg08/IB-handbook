The dot product, also known as the scalar product, is a measure of how much two [[Vectors (math)|vectors]] are pointing in the same direction. It is a large value when they align, zero when they're perpendicular, and negative when they are mostly opposite.

To calculate it, you can do the following.

$$
\vec{A}=
\begin{pmatrix}
x_{1} \\
y_{1} \\
z_{1}
\end{pmatrix}
$$
$$
\vec{B}=
\begin{pmatrix}
x_{2} \\
y_{2} \\
z_{3}
\end{pmatrix}
$$
$$
\vec{A}\cdot \vec{B}=(x_{1})(x_{2})+(y_{1})(y_{2})+(z_{1}+z_{2})
$$

>[!note]
>The dot product always yields a scalar value. Never a vector!

# Geometric interpretation

The dot product can also be thought of as a perpendicular line that is cast onto another vector. For instance, consider the vectors $\vec{V}_{AB}$ and $\vec{V}_{AC}$. These can be seen below.

![[two vectors.png|center|400]]

We can take the dot product of these two. The dot product, in essence, is as you'd draw a parallel from $\vec{V}_{AC}$ onto $\vec{V}_{AB}$. See the image below for the visual representation of this.

![[dot product vectors.png|center|400]]


We can also note that this causes a 'shadow' to be cast onto the the other vector, as seen below.

![[shadow of dot product vectors.png|center|400]]

This shadow can be calculated by multiplying the vector times the [[Cosine|cosine]] of the angle. Indeed, this is a simple use of the [[Trigonometric ratios|trigonometric ratios]]!
 
$$
\text{Shadow}=\vec{V}_{AC}\cdot \cos \theta
$$

However, we need the the angle ($\theta$) that is formed between these two vectors. You can get it with the following formula.

$$
\cos \theta=\frac{\vec{A}\cdot \vec{B}}{|\vec{A}||\vec{B}|}
$$

>[!note]
>That's right, this formula uses the dot product. That's what it's for!
