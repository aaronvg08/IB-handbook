The determinant of a matrix is similar to a multiplication, but instead of adding, you subtract. So far, to get the determinant of a matrix, it needs to be of 2x2 or 3x3.

### 2x2

For a 2x2 matrix, you simply have to multiply and subtract. Consider the following matrix.

$$
A=\begin{vmatrix}
2 & 2 \\
3 & 1
\end{vmatrix}
$$

The determinant of this matrix is given by cross-multiplying and subtracting.

$$
A=2(1)-2(3)
$$
$$
A=2-6
$$
$$
A=-4
$$

### 3x3

For a 3x3 matrix, you use the following technique. consider the following matrix.

$$
A=\begin{vmatrix}
3 & -1 & 3 \\
1 & 3 & 5 \\
0 & 1 & 0
\end{vmatrix}
$$

You take the first element of the first row, which is three. Then, you draw a T over it.

$$
A=\begin{vmatrix}
\cancel{ 3 } & \cancel{ -1 } & \cancel{ 3 } \\
\cancel{ 1 } & 3 & 5 \\
\cancel{ 0 } & 1 & 0
\end{vmatrix}
$$

This is a smaller 2x2 matrix! You simply multiply it by 3 to have it make sense, so.

$$
3\times\begin{vmatrix}
3 & 5 \\
1 & 0
\end{vmatrix}
$$

Then, you take the next element of the first row, which is -1. You do the same.

$$
A=\begin{vmatrix}
\cancel{ 3 } & \cancel{ -1 } & \cancel{ 3 } \\
1 & \cancel{ 3 } & 5 \\
0 & \cancel{ 1 } & 0
\end{vmatrix}
$$

This is another 2x2 matrix. Let's do as before.

$$
-1\times \begin{vmatrix}
1 & 5 \\
0 & 0
\end{vmatrix}
$$

Then, we do it for the last. The same process.

$$
A=\begin{vmatrix}
\cancel{ 3 } & \cancel{ -1 } & \cancel{ 3 } \\
1 & 3 & \cancel{ 5 } \\
0 & 1 & \cancel{ 0 }
\end{vmatrix}
$$
$$
3\times \begin{vmatrix}
1 & 3 \\
0 & 1
\end{vmatrix}
$$

Now, we arrange these. For this method to work, you do positive, negative, positive. So, the second term is always subtracting. Like so.

$$
\left(3\times\begin{vmatrix}
3 & 5 \\
1 & 0
\end{vmatrix}
\right)
-
\left(
-1\times \begin{vmatrix}
1 & 5 \\
0 & 0
\end{vmatrix}
\right)
+
\left(
3\times \begin{vmatrix}
1 & 3 \\
0 & 1
\end{vmatrix}
\right)
$$

We get the determinants of those sub-systems. So,

$$
3[3(0)-5(1)]+1[1(0)-5(0)]+3[1(1)-3(0)]
$$
$$
3(0-5)+1(0-0)+3(1-0)
$$
$$
3(-5)+1(0)+3(1)
$$
$$
-15+3
$$
$$
-12
$$

Therefore, the determinant of this entire matrix is -12.