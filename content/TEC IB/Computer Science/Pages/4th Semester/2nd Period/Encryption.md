Encryption in [[Cryptography|cryptography]] is the way in which we hide data in a computer so it can be sent or shared through the internet safely. Modern day encryption involves a key, which is normally a string or a character, that is passed through an [[NOR]] of the original message to transform it.

# Example

We have the following message: "aB". This can be represented in [[ASCII encoding|ASCII]] like this.

$$
\overbrace{ 01100001 }^{ a }\;\;\overbrace{ 01000010 }^{ B }
$$

Then, we choose a key. In this example, let's pick the letter "c", which in ASCII is 01100011. In order to encrypt this message with the key, we pass every character through the ASCII code of the key through a [[NOR]]. Here, let's place both characters ASCIIs over the key's ASCII.

$$
\begin{matrix}
01100001 & 01000010 \\
01100011 & 01100011 \\
\hline \\
\end{matrix}
$$

We pass each of these through the XOR.

$$
\begin{matrix}
01100001 & 01000010 \\
01100011 & 01100011 \\
\hline
00000010 & 00100001
\end{matrix}
$$

So, there is our encrypted message! 00000010 00100001. This is " !", a space and an exclamation point.

>[!note]
>Since we decrypt and encrypt with [[NOR]], it means that XOR is an operation that reverses itself!