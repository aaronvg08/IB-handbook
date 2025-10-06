Mathematical induction is a method of [[Proof|proof]] that is used to establish that a statement is true for all integer numbers. The main idea is that you assume that the statement is true for some integer number. Then you show, that if it is true for that natural number, then it is true for the next. And so on, and so on. Like dominoes, the statement is proved for all numbers.


![[proof by induction.png|center|450]]

Proof by induction has four main steps:

- **Base case**: Prove that the statement holds true for $n=1$. If it is, then go on. If not, the statement is immediately proved to be false.
- **Hypothesis**: Replace $n$ for $k$, which represents all natural numbers. Manipulate the initial statement to later insert it where it is beneficial. This is your hypothesis.
- **Inductive step**: Have faith and assume that the statement is true. Then, replace $n=k+1$, and manipulate the equation to insert the hypothesis. Solve until the left side is equal to the right side, or until you can see that it holds true.
- **Conclusion**: Interpret your result and state whether it was proved true or not.

# Example

We are going to prove that $3^{3n+3}-26n-27$ is divisible by 169 where $n\geq {1}$.

## Step 1: Base case

We prove the first case. We say that $n=1$.

$$
3^{3(1)+3}-26(1)-27
$$
$$
3^{6}-26-27=676
$$
$$
679 \div 169=4
$$

It can be divided, so the base case passes. We can move on.

## Step 2: Hypothesis

We make our hypothesis, so we say that $n=k$.

$$
3^{3k+3}-26k-27=169m
$$

We say $169m$, since that represents a multiple of 169. Next, we can pass the 27 to the other side.

$$
\boxed{3^{3k+3}-26k=169m+27}
$$

This is our hypothesis.

## Step 3: Inductive step.

Now, we state that $k+1$ and replace it in the original statement.

$$
3^{3(k+1)+3}-26(k+1)-27
$$

We manipulate the statement and try to find our hypothesis. Remember that $3^{3}\cdot3^{3}=3^{6}$. Therefore, we distribute and use the property.

$$
3^{3}\cdot 3^{3k+3}-26k-26-27=169m
$$

Look! Our hypothesis!

$$
3^{3}\cdot \boxed{3^{3k+3}-26k} -26-27=169m
$$

We substitute our hypothesis with the previous statement.

$$
3^{3}\cdot 169m +27-26-27=169m
$$
$$
27(169m +27)-26-27=169m
$$
$$
4563m+729-26-27=169m
$$
$$
4563m+676=169m
$$

Both 4563 and 676 are divisible by 169.

## Step 4: Conclude

Therefore, $3^{3n+3}-26n-27$ is divisible by 169 for $n\geq 1$.