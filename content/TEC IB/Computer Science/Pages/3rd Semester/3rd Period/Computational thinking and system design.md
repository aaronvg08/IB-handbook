Refers to ways of thinking and specific techniques that allow you to make a solution for a problem. There are six ways of thinking (for the IB lol):

- [[Thinking procedurally]].
- [[Thinking logically]].
- [[Thinking ahead]].
- [[Thinking concurrently]].
- [[Thinking abstractly]].
- [[Thinking recursively]].

There are also three main techniques (probably not, but for exam as of 09-09-2025 I am doing it like this):

- **Decomposition**: Divide a large and hard problem into small solvable problems.
- **Abstraction**: Focusing on the essential details of a problem to solve it and omit irrelevant details.
- **Pattern recognition**: Identify similarities, repetitive structures, and common characteristics between problems or within the same problem.
# Searching, sorting, and other algorithms on arrays

- **Variables:** In computer science, variables act as a storage location that can be used to store a value. Each variable has a name used to refer to the stored value. The value can be changed during program execution.

## One dimensional arrays or linear arrays

An array can hold multiple data elements of the same type. An array has a name, a size that cannot be changed during program execution and a data type that describes the type of data it can store. **We always start counting on zero.**

### Usage

```Python
A = array[]
H = 0
for i in H:
	A[i] = H+1

print(A[0])
```

## Parallel arrays

Useful when a programmer wants to store different properties of an entity. All elements should be of the same data type. Data is organized as a table. Each row represents a particular student, and all columns are of the same data type.

### Usage

```Python
names = ["May", "Eri", "Elen", "Rit", "Rato", "Ent"]
grades = [99, 98, 70, 100, 50, 57, 80, 90, 99]
```

## Arrays of objects

Is an array of reference variables. Each reference variable is an element of the array and its reference to an object.

### Usage

```Python
Vehicle1[Color:"red", Type:"car", Engine:2000]
Vehicle2[Color:"blue", Type:"bus", Engine:3000]
Vehicle3[Color:"blue", Type:"motorcycle", Engine:4000]
```