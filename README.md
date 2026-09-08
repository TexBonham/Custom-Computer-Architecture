# Custom-Computer-Architecture
 
An assembler and emulator for a custom instruction set architecture, written in C#
(started 2022). Programs are written in the ISA's assembly language, assembled to
machine code, and executed in the emulator.
 
**Scope:** the instruction set definition, a two-pass assembler, and an emulator
implementing the machine model — registers, memory, and the fetch/decode/execute
loop.
 
**Status:** complete and archived. This was the starting point of a line of
systems projects: the ideas here were later rebuilt and extended into
[CSharpOS](../../../CSharpOS), which runs a full operating system — virtual memory,
processes, signals, and a filesystem — on a redesigned custom ISA.
