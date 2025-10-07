Hexadecimal is a base-16 [[Number systems|number system]] that uses 16 symbols (numbers and letters) to represent values. It is a compact way of representing binary values.

> [!Note] 
> It is used in compilers and memory debugging.

| Hexadecimal | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | A   | B   | C   | D   | E   | F   |
| ----------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Decimal     | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  | 13  | 14  | 15  |

So, it’s the same as decimal but with different digits.

## Adding hexadecimal numbers

So, let’s imagine we’re adding $BCEAF_{16}+312_{16}$:

$$
\begin{matrix}
&&1&&1\\
&B&C&E&A&F \\  
+&&&3&1&2 \\  
\hline  
&B&D&1&C&1  
\end{matrix}
$$

So, why is $F+2=1$? Because we go to the table and add. In this case, we go back to the beginning. So: F, 0, 1, 2. Then, we carry a 1 to the next one, since we went back to the beginning of the table.
