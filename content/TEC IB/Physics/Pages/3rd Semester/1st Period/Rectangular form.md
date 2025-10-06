This is a specific format to write [[Vectors (physics)]] in. In rectangular form, the vector is described with the $x$ and $y$ coordinates. An example of a rectangular form is the following:

$$
\vec{A}=15i+10j
$$

```tikz
\begin{document}
  \begin{tikzpicture}[domain=0:4]
    \draw[very thin,color=gray] (-0.1,-1.1) grid (3.9,3.9);
    \draw[->] (-0.2,0) -- (4.2,0) node[right] {$x$};
    \draw[->] (0,-1.2) -- (0,4.2) node[above] {$y$};
    
    \draw[->] (0.2, 0.5) -- (3, 0.5);
    \draw[->] (3, 0.6) -- (3,2.8);
    \draw[->, thick] (0.2, 0.5) -- (3, 3);
    
    \draw (2, 0.3) node [black] {\textbf{$i=15$}};
    \draw (3.7, 2) node [black] {\textbf{$j=10$}};
  \end{tikzpicture}
\end{document}
```

> [!note]
> In rectangular form, $i=x$ and $j=y$. (As in, (x, y))

# Converting

To convert from rectangular form to [[Polar form (physics)]], we use the Pythagorean theorem to get the magnitude of the [[Displacement]], as if it was a triangle. Then, we can use the [[Vectors (physics)#Trigonometry|trigonometric ratios]] to get the angle from the x axis.

![[Rectangular to polar.png|center|350]]

> [!example]
> A vector in rectangular form of $\vec{A}=4j+3i$ is $\vec{A}=5\angle 36.86°$
