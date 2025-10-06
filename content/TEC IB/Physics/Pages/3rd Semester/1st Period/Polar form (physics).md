This is a specific format to write [[Vectors (physics)]] in. In polar form, the vector is described with its magnitude and angle relative to $x$. An example of polar form is the following:

$$
\vec{A}=\sqrt{ 325 }\angle33.69°
$$

```tikz
\usetikzlibrary{angles}
\begin{document}
  \begin{tikzpicture}[domain=0:4]
    \draw[very thin,color=gray] (-0.1,-1.1) grid (3.9,3.9);
    \draw[->] (-0.2,0) -- (4.2,0) node[right] {$x$};
    \draw[->] (0,-1.2) -- (0,4.2) node[above] {$y$};
    
    \coordinate (a) at (0,0);
    \coordinate (b) at (3,3);
    \coordinate (c) at (4.2,0);
    
    \draw[->, thick] (0, 0) -- (3, 3);
    
    \draw (1, 2) node [black] {\textbf{$\sqrt{325}$}};
    \draw (0.7, 0.3) node [black] {\textbf{$\theta$}};
    
    \pic[draw] {angle=c--a--b};
    
  \end{tikzpicture}
\end{document}
```

$$
\theta=33.69°
$$

> [!note]
> Here, we express the vector with the magnitude and the angle instead of "steps" like in rectangular form.

# Converting

To convert a vector in polar form into [[Rectangular form]], we use the [[Vectors (physics)#Trigonometry|trigonometric ratios]] to get the $x$ and $y$ parts of the magnitude.

![[Polar to rectangular.png|center]]

> [!example]
> A polar-form vector of $\vec{A}=5\angle45°$ would be $\vec{A}=0.52i+0.85j$.
