Sometimes, when solving a problem, we have to do something over and over and over again. This is called brute-forcing, but in [[Computer Science|computer science]], we use flowery language.

Recursion is when a method calls itself until some terminating condition is met. This is done without a while or a for loop, or any repetition construct. 

The following program uses recursion to create the method `addIntUpTo(n)` for $n>0$ that will add all numbers from and including $n$ down to 1.

```python
def addIntUpTo(n)
	if n == 1:
		return 1
	else:
		return n + addIntUpTo(n-1)
```

>[!note]
>As you can see, we never use a while or for loop here. However, we call the method within the method!

# Tracing recursive algorithms

In order to trace recursive algorithms, you can think that a new algorithm opens up within the algorithm. For instance, consider the following code.

```python
def addIntUpTo(n)
	if n == 1:
		return 1
	else:
		return n + addIntUpTo(n-1)

```

If you run `addIntUpTo(4)`, this code can also be seen like this.

```python
addIntUpTo(4)
    └── addIntUpTo(3)
          └── addIntUpTo(2)
                └── addIntUpTo(1) ==> returns 1
                <== returns 3 (2 + 1)
          <== returns 6 (3 + 3)
    <== returns 10 (4 + 6)
```