Compilers translate the entire high-level code of a program into machine code in a single process before the program is executed.

![[compiler.png|center|600]]

Compilers have several stages.

- **Lexical analysis**: Scans the code and breaks it down into tokens.
- **Syntax analysis**: Checks if the code follows the program rules.
- **Semantic analysis**: Verifies the logic and operators of the code.
- **Optimization**: Improves the code to make it run faster.
- **Code generation**: Translates high-level to the machine code.

>[!success]
>The nice thing is that compilers detect errors during the translation process and don't generate the program unless the code is correct.

# Just In Time (JIT) compilation

![[Just In Time (JIT) compilation]]