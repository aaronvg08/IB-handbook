Decryption in [[Cryptography|cryptography]] is the way in which we turn [[Encryption|encrypted]] messages back into their original form. Modern day decryption involves a key, which is normally a string or a character, that is passed through an [[XOR]] of the encrypted message to decrypt it.

# Example

We have the following encrypted message: " !". A space and an exclamation mark.

$$
00000010\;\;00100001
$$

We have the key! Which in this case is the character "c" in lowercase. In ASCII, this is 01100011. In order to decrypt this message with the key, we pass every encrypted character through the ASCII code of the key through an [[XOR]]. Here, let's place both character's ASCIIs over the key's ASCII.

$$
\begin{matrix}
00000010 & 00100001 \\
01100011 & 01100011 \\
\hline
\end{matrix}
$$

We pass each of these through the XOR.

$$
\begin{matrix}
00000010 & 00100001 \\
01100011 & 01100011 \\
\hline
01100001 & 01000010
\end{matrix}
$$

And there is our decrypted message! 01100001 01000010. This is "aB".

>[!note]
>Since we decrypt and encrypt with [[XOR]], it means that XOR is an operation that reverses itself!