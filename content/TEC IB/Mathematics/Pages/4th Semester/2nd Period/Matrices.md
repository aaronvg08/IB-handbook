A matrix is a complex mathematical object that involves a rectangular array of objects. It can be represented with both brackets or parenthesis. It looks something like this.

$$
A=\\begin{bmatrix}
1 \& 2 \& 3 \\
4 \& 5 \& 6
\\end{bmatrix}
$$

A matrix's dimensions are measured in rows x columns. So, for the matrix above ($A$), the dimensions are 2x3.

# Operations

Since matrices are mathematical objects, you can perform operations on them. These include the usual operations of addition, subtraction, and other special operations.

## Addition \& subtraction

Addition between matrices is how you would expect. In order to add two matrices, they must have the same dimensions. For instance, take the following matrices.

$$
A=\\begin{bmatrix}
1 \& 5 \& 1 \\
4 \& 3 \& 2 \\
0 \& -5 \& 1
\\end{bmatrix}
$$
$$
B=\\begin{bmatrix}
0 \& 4 \& 1 \\
9 \& -1 \& 2 \\
1 \& 10 \& 2
\\end{bmatrix}
$$

The addition of these two matrices are as follows.

$$
A+B=\\begin{bmatrix}
(0+1) \& (5+4) \& (1+1) \\
(9+4) \& (3-1) \& (2+2) \\
(0+1) \& (-5+10) \& (2+1)
\\end{bmatrix}
$$
$$
A+B=\\begin{bmatrix}
1 \& 9 \& 2 \\
13 \& 2 \& 4 \\
1 \& 5 \& 3
\\end{bmatrix}
$$

Simple! And subtraction works the same way.

## Multiplication

In order to multiply matrices, their dimensions have to line up with the following rule: the amount of columns for the first matrix has to line up with the amount of rows. The result of a multiplication is another matrix that has the same number of rows as the 1st matrix and the same number of columns as the 2nd matrix.

Consider the following matrices.

$$
A=\\begin{bmatrix}
2 \& 3 \& 1 \\
2 \& 2 \& 2
\\end{bmatrix}
$$
$$
B=\\begin{bmatrix}
2 \& 2 \\
1 \& 1 \\
0 \& -1
\\end{bmatrix}
$$

The first matrix's dimensions are 2x3, and the second are 3x2. Therefore, since the last number of the first matrix and first number of the last matrix match up, these matrices can be multiplied. We know that the resulting matrix will be of 2x2.

$$
A\\cdot B=\\begin{bmatrix}
? \& ? \\
? \& ?
\\end{bmatrix}
$$

We do so by taking the rows of the first and putting them against the columns, so:

$$
\\begin{bmatrix}

\\boxed2 \& \\boxed3 \& \\boxed1 \\\\

2 \& 2 \& 2

\\end{bmatrix}

\\times

\\begin{bmatrix}

\\boxed2 \& 2 \\\\

\\boxed1 \& 1 \\\\

\\boxed0 \& {-1}

\\end{bmatrix}
$$
$$
2(2)+3(1)+1(0)=4+3+0
$$
$$
=7
$$

Therefore, this is the result of our first element.

$$
A\\cdot B=\\begin{bmatrix}
7 \& ? \\
? \& ?
\\end{bmatrix}
$$

We take the same row, and put it against the next column of the next matrix.

$$
\\begin{bmatrix}
\\boxed2 \& \\boxed3 \& \\boxed1 \\
2 \& 2 \& 2
\\end{bmatrix}
\\times
\\begin{bmatrix}
2 \& \\boxed2 \\
1 \& \\boxed1 \\
0 \& \\boxed{-1}
\\end{bmatrix}
$$
$$
2(2)+3(1)+1(-1)=4+3-1
$$
$$
=6
$$

That's the next result.

$$
A\\cdot B=\\begin{bmatrix}
7 \& 6 \\
? \& ?
\\end{bmatrix}
$$

Then, we go to the next row and do the same!

$$
A\\cdot B=\\begin{bmatrix}
7 \& 6 \\
2(2)+2(1)+2(0) \& 2(2)+2(1)+2(-1)
\\end{bmatrix}
$$
$$
A\\cdot B=\\begin{bmatrix}
7 \& 6 \\
4+2+0 \& 4+2-2
\\end{bmatrix}
$$
$$
A\\cdot B=\\begin{bmatrix}
7 \& 6 \\
6 \& 4
\\end{bmatrix}
$$

And there you have it!

## Determinant

The determinant of a system is similar to a multiplication, but instead of adding, you subtract. So far, to get the determinant of a matrix, it needs to be of 2x2 or 3x3.

### 2x2

For a 2x2 matrix, you simply have to multiply and subtract. Consider the following matrix.

$$
A=\\begin{vmatrix}
2 \& 2 \\
3 \& 1
\\end{vmatrix}
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
A=\\begin{vmatrix}
3 \& -1 \& 3 \\
1 \& 3 \& 5 \\
0 \& 1 \& 0
\\end{vmatrix}
$$

You take the first element of the first row, which is three. Then, you draw a T over it.

$$
A=\\begin{vmatrix}
\\cancel{ 3 } \& \\cancel{ -1 } \& \\cancel{ 3 } \\
\\cancel{ 1 } \& 3 \& 5 \\
\\cancel{ 0 } \& 1 \& 0
\\end{vmatrix}
$$

This is a smaller 2x2 matrix! You simply multiply it by 3 to have it make sense, so.

$$
3\\times\\begin{vmatrix}
3 \& 5 \\
1 \& 0
\\end{vmatrix}
$$

Then, you take the next element of the first row, which is -1. You do the same.

$$
A=\\begin{vmatrix}
\\cancel{ 3 } \& \\cancel{ -1 } \& \\cancel{ 3 } \\
1 \& \\cancel{ 3 } \& 5 \\
0 \& \\cancel{ 1 } \& 0
\\end{vmatrix}
$$

This is another 2x2 matrix. Let's do as before.

$$
-1\\times \\begin{vmatrix}
1 \& 5 \\
0 \& 0
\\end{vmatrix}
$$

Then, we do it for the last. The same process.

$$
A=\\begin{vmatrix}
\\cancel{ 3 } \& \\cancel{ -1 } \& \\cancel{ 3 } \\
1 \& 3 \& \\cancel{ 5 } \\
0 \& 1 \& \\cancel{ 0 }
\\end{vmatrix}
$$
$$
3\\times \\begin{vmatrix}
1 \& 3 \\
0 \& 1
\\end{vmatrix}
$$

Now, we arrange these. For this method to work, you do positive, negative, positive. So, the second term is always subtracting. Like so.

$$
\\left(3\\times\\begin{vmatrix}
3 \& 5 \\
1 \& 0
\\end{vmatrix}
\\right)
---

\\left(
-1\\times \\begin{vmatrix}
1 \& 5 \\
0 \& 0
\\end{vmatrix}
\\right)
+
\\left(
3\\times \\begin{vmatrix}
1 \& 3 \\
0 \& 1
\\end{vmatrix}
\\right)
$$

We get the determinants of those sub-systems. So,

$$
3\[3(0)-5(1)]+1\[1(0)-5(0)]+3\[1(1)-3(0)]
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

