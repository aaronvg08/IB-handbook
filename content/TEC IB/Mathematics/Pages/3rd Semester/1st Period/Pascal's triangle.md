Pascal's triangle is an infinite triangular array of the binomial coefficients which play a crucial role in probability theory, combinatorics, and algebra. It's main use is that can [[Binomial expansion|expand binomials]].

![[pascals triangle.png|center]]

# Expanding binomials

Say we want to expand the following binomial:

$$
(x-2){^3}
$$
In order to do so, we can see the exponent (in this case $3$), and check the row in pascal's triangle that has that number right away, in this case the 4th row ($1, 3,3,1$). And so, we do the following:

$$
(x-2){^3}=1(x){^3}(-2){^0}+3(x){^2}(-2){^1}+3(x){^1}(-2){^2}+1(x){^0}(-2){^3}
$$
$$
(x-2){^3}=x{^3}-6x{^2}+12x-8
$$

>[!note]
>Be aware that there are better ways of doing this, since memorizing pascal's triangle is cumbersome. Just know that it is possible, and it is a way to expand.