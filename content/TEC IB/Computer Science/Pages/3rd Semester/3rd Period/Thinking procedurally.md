When a particular problem has to be solved, an effective method or procedure should be identified. This procedure reduces the solution to a series of simple steps. These steps have to be followed in the correct order to obtained the desired output.

>[!example]
>It is impossible to ride a motorcycle if you don't know how to ride a bicycle! First, you have to learn to ride the bicycle to ride the motorcycle.

Procedural proceses look like this. One after the other.

![[procedural thinking.png|center|650]]

# Sub-procedures

It is important to understand how sub-procedures help when solving a problem. What we mean by sub-procedures is to break up a problem into smaller sub-problems.

For example, let's imagine a program that calculates the solutions of a quadratic equation. A sub-procedure called discriminant could be used to calculate the discriminant "D". That algorithm could look something like this.

```pseudocode
Input a, b, c
D=Call Sub-procedure Discriminant that returns value D

If D>0 then
	calculate x1 = (-b+sqrt{D})/(2a)
	calculate x2 = (-b-sqrt{D})/(2a)
Else if D=0 then
	Calculate x1 = (-b+sqrt{D})/(2a), x2 = (-b-sqrt{D})/(2a)
Else
	Output no solutions
End if

Output x1, x2

Sub-procedure Discriminant
	Calculate D=b^2-4*a*c
	Return D
```