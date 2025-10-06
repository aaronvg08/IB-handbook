Binary is a type of [[Number systems|number system]] and the language of modern-day computers. It has only 2 possible states: 0 and 1.

- 1 - ON / TRUE
- 2 - OFF / FALSE

It reduces the complexity of hardware design and enhances reliability. It is more robust to noisy environments since it is just on and off.

| multiplier (power of two) | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **multiplier**            | 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |

# How to use

| multiplier (power of two) | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| multiplier                | 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |
| digits                    |       |       | 1     | 0     | 1     | 1     | 1     | 0     |

To calculate the decimal value represented by the binary number 101110 we must multiply every digit of the number with its respective multiplier and then sum the results, as such:

$$0*1+1*2+1*4+1*8+0*16+1*32=?$$
$$
0+2+4+8+0+32=46
$$

So, if we want to represent 134:

| multiplier (power of two) | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| multiplier                | 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |
| digits                    | 1     | 0     | 0     | 0     | 0     | 1     | 1     | 0     |

= 10000110

$$128+4+2=134$$

# Negatives

- Two’s complement is the way most modern computer represented signed binary numbers.
- MSB (most significant bit) left-most bit.
- LSB (least significant bit) right-most bit.

So, how do we do it? Imagine we’re writing 28 in binary. We want to do it in 8 bits.

| multiplier (power of two) | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| multiplier                | 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |
| digits                    | 0     | 0     | 0     | 1     | 1     | 1     | 0     | 0     |

$$00011100_{2}=28_{10}$$

> [!important] The subscript is the number system. Two is binary, since it’s only 0 and 1. 28 is 10, because it’s from 0-9.

So, it’s 00011100. It’s fine if we have zeroes on the left. How do we turn it into negative? First, we turn all the zeroes into ones, and ones into zeroes. We invert it.

$$00011100>>11100011$$

Now we have 11100011. Now we add a one in the following way:

$$\begin{matrix}  
&1&1&1&0&0&0&1&1 \\  
+&&&&&&&&1 \\  
\hline  
&1&1&1&0&0&1&0&0  
\end{matrix}$$

So, signed $11100100_{2}=-28_{10}$.

## How do we know a number is a negative??

There are two types of values: signed and unsigned. Signed is for negative numbers, and unsigned is the “normal” binary system. So for example:

The numbers we can represent with unsigned with 8 bits is: 0…255

The numbers we can represen with signed with 8 bits is: -128…127

Why? Because if we want to represent 128 with unsigned, it would be $10000000$. However, if we try to do 128 with signed, we can’t. The first digit of a signed value expresses if it’s positive or negative, which is why it’s called the MSB, so it’s impossible to do it.

# Fractions

So, what actually happens when a number is a fraction? We do $1^{-1}$ or any number by -1, and put a dot. Let’s imagine the table again, but with decimal.

| multiplier (power of two) | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | **.** | $2^0$ | $2^{-1}$ | $2^{-2}$ | $2^{-3}$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | -------- | -------- | -------- |
| multiplier                | 32    | 16    | 8     | 4     | 2     |       | 1     | 1/2      | 1/4      | 1/8      |

So, now imagine we want to write 31.875 in binary:

| multiplier (power of two) | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ | **.** | $2^{-1}$ | $2^{-2}$ | $2^{-3}$ |
| ------------------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | -------- | -------- | -------- |
| multiplier                | 32    | 16    | 8     | 4     | 2     | 1     |       | 1/2      | 1/4      | 1/8      |
| digits                    | 0     | 1     | 1     | 1     | 1     | 1     | .     | 1        | 1        | 1        |

= 31.875

## Fraction and negative?

So now let’s turn that into negative.

$$011111.111>>100000.000$$

$$\begin{matrix}  
&1&0&0&0&0&0&.&0&0&0 \\  
+&&&&&&&&&&1 \\  
\hline  
&1&0&0&0&0&0&.&0&0&1  
\end{matrix}$$

So, -31.875 would be signed $100000.001$.

# Conversions

## Hexadecimal

>[!quote]
>> _“Very fucking stupid”_  
>
>-Murillo

How do we go from binary to [[Hexadecimal|hexadecimal]] without going through [[Decimal (number system)|decimal]] first?

$$011001011$$

You divide each, by four

$$0|1100|1011$$

Then we do each individually.

$$\begin{matrix}  
0&|&1100&|&1011\\  
0&&C&&B  
\end{matrix}$$

So, it’d be $0CB_{16}$ .

## Octal

How do we convert to [[Octal|octal]] without going through [[Decimal (number system)|decimal]] first?

$$
011001011
$$

You divide each by three.

$$
011|001|011
$$

Then we do each individually.

$$
\begin{matrix}  
011&|&100&|&011\\  
3&&4&&3  
\end{matrix}
$$

So, it'd be $343_{16}$ .