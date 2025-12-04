# What are they?

Computer systems are made up of electrical circuits and use the [[Binary|binary system]] to represent and store data. Electrical circuits have been designed to receive one or more binary numbers as their inputs and produce a single output. The logical operations of these circuits are governed by the rules of Boolean logic.

The logical operations are carried out by the 6(3) Boolean Operators we have:

- [[AND]]
- [[OR]]
- [[NOT]]
- [[NAND]]
- [[NOR]]
- [[NOR]]
- [[XNOR]]

> [!important]
>  When solving boolean operators, you **always** go right to left, unlike in math.

> [!note] 
> NAND, NOR, XOR and XNOR can all be represented only using AND, OR, and NOT.

## AND

![[AND]]

## OR

![[OR]]

## NOT

![[NOT]]

## NAND

![[NAND]]

## NOR

![[NOR]]

## XOR

![[XOR]]

## XNOR

![[XNOR]]

# Properties

Thins that apply and are ‘rules’ for systems that always work that way. Most work kind of like math, which is why the mathematical symbols are used. It’s a way to simplify complex logical statements.

## Identity

$$A+0=A\\  
A*1=A$$

## Idempotency

$$A+A=A\\  
A*A=A$$

## Complement

$$A+!A=1$$

## Involution

$$!(!A)=A$$

## Null

$$A+1=1\\  
A*0=0$$

  

## Associative

> [!info] Same with AND (*)

$$A+B+C\\(A+B)+C\\A+(B+C)$$

## Commutative

$$A+B=B+A$$

  

## Distributive

$$A(B+C)=AB+AC\\  
A+(BC)=(A+B)*(A+C)$$

## Absorption

$$A+(A*B)=A\\  
A(A+B)=A$$

## Simplification

> [!info] We’re using 2 different properties for this one.

$$A+(A'B)=A+B$$

## Adjacency

$$(AB)+(A!B)=A$$

## DeMorgan

$$!(A+B)=!A!B\\  
!(AB)=!A+!B$$

  

## Consensus

$$(A*X)+(A'*Y)+(X*Y)=(A*X)+(A'*Y)$$