The nth roots theorem is a rule in [[Complex numbers|complex numbers]] that helps us find the roots of any complex number. It states that for a complex number in [[Polar form (math)|polar form]], we can use the following formula.

$$
\sqrt[n]{ M }\left( \cos\left( \frac{\theta+2\pi k}{n} \right)+i\sin\left( \frac{\theta+2\pi k}{n} \right) \right)
$$

Where $M$ is the magnitude, $\theta$ is the angle, $n$ is the number of roots we want to find, and $k$ is the solution we are currently finding, where $k=0,1,2,3\dots n-1$.

# Example

To get the cubic roots of $z=8\left( \cos\left( \frac{2\pi}{3} \right)+i\sin\left( \frac{2\pi}{3} \right) \right)$, we use the formula. From the [[Fundamental theorem of algebra|fundamental theorem of algebra]], we know we are looking for 3 solutions. So, $n=3$.

For $k=0$,

$$
\sqrt[3]{8}\left( \cos\left( \frac{\frac{2\pi}{3}+2\pi \cdot0}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}+2\pi \cdot 0}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{\frac{2\pi}{3}}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{2\pi}{3} \right)+i\sin\left( \frac{2\pi}{3} \right) \right)
$$

For $k=1$,

$$
\sqrt[3]{8}\left( \cos\left( \frac{\frac{2\pi}{3}+2\pi \cdot 1}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}+2\pi \cdot 1}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{\frac{2\pi}{3}+2\pi}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}+2\pi}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{8\pi}{9} \right)+i\sin\left( \frac{8\pi}{9} \right) \right)
$$

For $k=2$,

$$
\sqrt[3]{8}\left( \cos\left( \frac{\frac{2\pi}{3}+2\pi \cdot 2}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}+2\pi \cdot 2}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{\frac{2\pi}{3}+4\pi}{3} \right)+i\sin\left( \frac{\frac{2\pi}{3}+4\pi}{3} \right) \right)
$$
$$
2\left( \cos\left( \frac{14\pi}{9} \right)+i\sin\left( \frac{14\pi}{9} \right) \right)
$$

And that's it! We have all the complex cube roots for $z=8\left( \cos\left( \frac{2\pi}{3} \right)+i\sin\left( \frac{2\pi}{3} \right) \right)$.

# Polynomials

We can express any number, even a real number, as a complex number. This means that if we treat certain polynomial equations as complex numbers, we can find all of their complex roots by using this theorem.

For instance, consider the following equation.

$$
x^{4}+16=0
$$

If we isolate $x^{4}$ as if it was a complex number,

$$
x^{4}=-16
$$

And then we transform -16 to polar form,

$$
x^{4}=16(\cos \pi+i\sin \pi)
$$

Why $\pi$? Because 16 is negative. It is $\pi$ [[Radians|radians]] rotated onto the negative line. 

And now, this is the same as saying "get the 4th roots of $16(\cos \pi+i\sin \pi)$." If we evaluate, the solutions of this equation are the following

$$
\begin{matrix}
x_{1}=\sqrt{ 2 }+\sqrt{ 2 }i \\
x_{2}=-\sqrt{ 2 }+\sqrt{ 2 }i  \\
x_{3}=\sqrt{ 2 }-\sqrt{ 2 }i \\
x_{4}=-\sqrt{ 2 }-\sqrt{ 2 }i
\end{matrix}
$$

>[!note]
>Do you see how all of them are conjugates of each other? This also demonstrates the [[Complex conjugates theorem|complex conjugate theorem]]!

>[!warning]
>This technique only works when you can easily isolate the polynomial into the form $x^{n}=a$. Otherwise, you may need to factor or do other techniques.