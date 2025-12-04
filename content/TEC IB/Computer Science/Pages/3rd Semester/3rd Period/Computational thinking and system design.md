Refers to ways of thinking and specific techniques that allow you to make a solution for a problem. There are six ways of thinking (for the IB lol):

- [[Thinking procedurally]]
- [[Thinking logically]]
- [[Thinking ahead]]
- [[Thinking concurrently]]
- [[Thinking abstractly]]
- [[Thinking recursively]] (HL)

There are also three main techniques (probably not, but for exam as of 09-09-2025 I am doing it like this) for dealing with problems:

- **Decomposition**: Divide a large and hard problem into small solvable problems.
- **Abstraction**: Focusing on the essential details of a problem to solve it and omit irrelevant details.
- **Pattern recognition**: Identify similarities, repetitive structures, and common characteristics between problems or within the same problem.

# Programing algorithms

## Search
### Linear search

Linear search is a programming algorithm that searches elements in a list, in which each element is checked in sequential order. To find the key you must use a loop to check the entire list starting at position 0. Stop the loop when the key is found.

- **Best-case scenario**: The item is found in the first position.
- **Worst-case scenario**: The item is the last item of the list.

### Binary search

Binary search is a programming algorithm that searches elements in an ordered list. It does so by repeatedly checking the value of the middle element and disregarding the half of the data structure that doesn't contain the searched element.

## Sorting

### Bubble sort

Bubble sort is a programming algorithm that sorts elements in a list. It does so by comparing adjacent values and swaps them if they are in an incorrect order.

- Start at the beginning of the array.
- Compare the current element with the next one.
- If the two values aren't in order, swap them.
- Move to the next element in the array.
- Repeat the process until all elements are sorted.

### Selection sort

Selection sort is a programming algorithm that sorts elements in a list. It does so by repeatedly selecting the smallest or largest element from the list and moving it to the beginning, and repeating while ignoring already sorted elements.

>[!warning]
>This sorting algorithm doesn't allow for an early exit if the array is ordered at an earlier point.


