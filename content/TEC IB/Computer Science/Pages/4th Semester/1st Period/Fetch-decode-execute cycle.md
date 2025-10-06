The fetch-decode-execute cycle is the fundamental cycle of instruction execution in a computer. this cycle is also known as the instruction cycle. When you run a program, it is executed by your [[Central Processing Unit (CPU)|CPU]]. The fetch-decode-execute cycle describes how instructions are executed.

It consists of three main steps:

1. **Fetch**: The CPU fetches an instruction from memory.
2. **Decode**: The CPU decodes the instruction, which means it breaks down the instruction into a set of low-level operations that it can execute.
3. **Execute**: The CPU executes the instruction, which means it carries out the low-level operations that were specified in the decoded instruction.

This cycle is repeated many times for each instruction in a program. The speed of the CPU is largely determined by how fast a computer can execute this cycle.

# Phases

## Fetch

In the fetch phase, the CPU retrieves a machine language instruction from the [[Primary memory|primary memory]] (typically the [[Random Access Memory (RAM)|RAM]]). This involves the CPU sending a request to the memory to fetch the instruction. The address of the instruction fetched is stored in the [[Memory Address Register (MAR)|memory address register (MAR)]], and the fetched instruction is then transferred to the [[Instruction Register (IR)|instruction register (IR)]].

## Decode

In the decode phase, the CPU interprets the machine language instruction fetched during the previous phase. This phase is managed primarily by the [[Control Unit (CU)|control unit (CU)]], which decodes the instruction by analyzing these components:

- **Opcode (operation code)**: The type of operations.
- **Operands**: The data to be operated on.
- **Addressing modes**: Determine how to locate the operands.

Additionally, the decode phase involves checking the validity of the instruction and ensuring that the operands are within an acceptable range.

## Execute

During the execute phase, the CPU performs the operation specified by the instruction decoded in the previous phase. The specific operation carried out is dictated by the opcode. Common operations include:

- Arithmetic operations.
- Logical operations.
- Memory access operations.
- Control operations.
