Arrays in programming are [[Abstract data structures|abstract data structures]] that represent lists of [[Data Types|variables]] that have a specific index, often starting to count from 0 rather than one.

```python
my_array = [0, 0, 2, "hi!", False]
```

## One dimensional arrays or linear arrays

One dimensional arrays are simple arrays that hold values linearly. They are the kind of list you would expect, and they are regarded quite simply.
### Usage

```Python
A = array[]
H = 0
for i in H:
	A[i] = H+1

print(A[0])
```

## Two dimensional arrays

An array can also have other arrays inside. This is what's known as a two-dimensional array. It can be used to represent a table, like the one below.

|            |         | Exam 1  | Exam 2  | ... | Exam 5  |
| ---------- | ------- | ------- | ------- | --- | ------- |
|            |         | Index 0 | Index 1 |     | Index 4 |
| Student 1  | Index 0 | 99      | 68      |     | 90      |
| Student 2  | Index 1 | 89      | 70      |     | 98      |
| ...        | ...     | ...     | ...     |     | ...     |
| Student 10 | Index 9 | 74      | 100     |     | 100     |

## Usage

```python
scores = 
[[98,68,65,73,67],
[77,77,88,78,90],
[53,63,74,85,72],
[77,77,68,78,91],
[88,86,90,56,81]]

for student in range(4)
	print(student + 1 + "student")
	for exam from range (4)
		print("--- Exam " + str(exam + 1) + scores[student][exam])
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