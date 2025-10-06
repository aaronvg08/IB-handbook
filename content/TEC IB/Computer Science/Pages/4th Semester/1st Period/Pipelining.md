Pipelining is a process that allows a [[Central Processing Unit (CPU)|processor]] to execute multiple instructions at the same time, which can significantly improve the overall efficiency of the system.

This is faster than independent execution, which looks something like this:

```mermaid
graph LR;
	1["Task 1"]-->B["Task 2"] --> C["Task 3"];
```

Essentially, you wait for each task to finish before starting the next. This is inefficient, and pipelining fixes that.
# Example

## Non-pipelined laundry

1. **Wash**: Put a load of clothes in the washing machine and wait for the cycle to finish.
2. **Dry**: Transfer the wet clothes to the dryer and wait for them to dry.
3. **Fold**: Take the dry clothes out and fold them.

## Pipelined laundry

1. **Wash (Load A)**: Put the first load of clothes in the washing machine.
2. **Dry(Load A)**: When Load A finishes washing, transfer it to the dryer.
3. **Wash (Load B)**: While Load A is drying, start a second load of laundry in the washing machine.
4. **Fold (Load A)**: When Load A finishes drying, fold the clothes.
5. **Dry (Load B)**: When Load B finishes washing, transfer it to the dryer.
6. **Wash (Load C)**: While Load B is drying, start a third load of laundry in the washing machine.
7. **Fold (Load B)**: When Load B finishes drying, fold the clothes
8. Etc.
