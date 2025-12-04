Interpreters translate high-level programming languages into machine code line-by-line or statement-by-statement, executing each line as it is being translated.

It doesn't generate an executable file since the code runs one line at a time. This also means that errors can rise if there is a mistake in the code.

![[interpreter.png|center|600]]

>[!important]
>Some interpreters run code through generating [[Bytecode|bytecode]] instead of directly making it machine code.

>[!bug]
>Interpreters detect errors at runtime, so it is useful for identifying and correcting errors during development as well as [[Debugging|debugging]].