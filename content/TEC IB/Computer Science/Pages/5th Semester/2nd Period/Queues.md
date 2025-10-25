A queue is an [[Abstract data structures|abstract data structure]] that stores a set of elements in a particular order. It allows access only to the first item inserted, and items as a whole are retrieved in the order in which they are inserted.

>[!note]
>Queues are a First-in, First Out (FIFO) data structure.

Queues utilize three methods:

- `enqueue()`: Pushes an item onto a stack.
- `dequeue()`: Removes and returns the last item entered in the stack.
- `isEmpty()`: Tests if a stack is empty. It returns true if a stack contains no elements. False otherwise.

![[queues.png|center|600]]

# Applications

- Queues are used to model physical queues, such as people waiting at a supermarket checkout.
- The print queue displays the amount of documents that are waiting to be printed. These documents follow the first-sent first-printed policy.
- When sending data over the internet, various data packets wait in a queue to be sent.
- A server usually serves various requests. In most cases these are stored in a queue. The first-come first-serve request procedure is followed.