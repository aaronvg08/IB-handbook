The geometric mean is a [[Central tendency measures|central tendency measure]] that is used for something that is measured in a logarithmic scale, such as decibels, pH in a substance, pain perception, etc. It can be acquired with the product of all the data in the nth root, where $n$ is the number of values.

$$
\sqrt[n]{\prod_{i=1}^{n}(a_{i})}
$$

>[!question] Pi notation
>The definition above uses pi notation, which is basically the same as [[Sigma notation|sigma notation]] but instead of a sum, it is the product!

# Example

For instance, take the following dataset.

$$
a=\{20,25,30,42,50\}
$$

The geometric mean is the following.

$$
\mu_{g}=\sqrt[5]{20\cdot 50 \cdot 30 \cdot 42 \cdot 50 }
$$
$$
\mu_{g} =31.5981
$$

>[!danger]
>A major weakness of the geometric mean is that if we have an odd number of negative values, the result will be [[Complex numbers|imaginary]].

