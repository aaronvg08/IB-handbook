A flowchart is used to diagrammatically describe an [[Algorithm]]. The following symbols are widely accepted:

[![](https://www.smartdraw.com/flowchart/img/basic-symbols-table.jpg)](https://www.smartdraw.com/flowchart/img/basic-symbols-table.jpg)

# Start/end

To mark the start and end of an algorithm.

> [!important] Despite having a finite number of steps, it may not always end anyway.


```mermaid
flowchart TD
  1([Start/end])
```

# Declaration/assignment

Declare a variable.

```mermaid
graph TD
  Declaration
```

# Decision

Can be used for:

- If
- While
- For

```mermaid
flowchart TD
  1d{Decision}
```

# Call a method/function

Use a method or a function. Can receive input, in the same box.

```mermaid
flowchart TD
  1[[Call a method/function]]
```