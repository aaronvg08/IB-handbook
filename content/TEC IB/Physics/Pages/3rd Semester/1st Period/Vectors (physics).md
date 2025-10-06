Vectors are ways to analyze space, and how one point travels to another. 

# Trigonometry

We all know the way you can get the sides of a triangle with trigonometric ratios.

$$
\sin \theta=\frac{opposite}{hypothenuse}
$$
$$
\cos \theta=\frac{adjacent}{hypothenuse}
$$
$$
\tan \theta=\frac{opposite}{adjacent}
$$
```tikz
\usetikzlibrary{angles}
\begin{document}
  \begin{tikzpicture}
    \coordinate (a) at (0,0);
    \coordinate (b) at (3,3);
    \coordinate (c) at (3,0);
    
    \draw[thick] (a) -- (b) -- (c) -- cycle;
    
    \pic[draw] {angle=c--a--b};
     
    \draw (0.7, 0.3) node [black] {\textbf{$\theta$}};
    \draw (1.3,2) node [black, rotate=43] {\textbf{hypothenuse}};
    \draw (3.3,1.5) node [black, rotate=-90] {\textbf{opposite}}; 
    \draw (1.5,-0.3) node [black] {\textbf{adjacent}};
       
  \end{tikzpicture}
\end{document}
```
# Forms

## Rectangular form

![[Rectangular form]]
## Polar form

![[Polar form (physics)]]