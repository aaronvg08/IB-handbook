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