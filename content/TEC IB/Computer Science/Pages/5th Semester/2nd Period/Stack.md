A stack is an [[Abstract data structures|abstract data structure]] that stores a set of elements in a particular order. It allows access only to the last item inserted, and items as a whole are retrieved in the reverse order in which they are inserted.

>[!note]
>Stacks are a Last-in, First Out (LIFO) data structure.

Stacks utilize three methods:

- `push()`: Pushes an item onto a stack.
- `pop()`: Removes and returns the last item entered in the stack.
- `isEmpty()`: Tests if a stack is empty. It returns true if a stack contains no elements. False otherwise.

![[stacks.png|center|600]]

# Applications

- The back button of a web browser uses a stack to function. Every time a URL is visited it is stored on a stack. The last address that was visited is on the top of the stack. The first address that was visited during the current web session is on the bottom. 
- Microprocessors usually use a stack to handle methods.
- [[Thinking recursively|Recursive]] methods also utilize the system stack to keep track of each recursive call.
