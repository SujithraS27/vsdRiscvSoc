
## Task 5: ABI and Register cheat sheet
---
### 🎯 Objective

List all 32 RV32 integer registers along with their:

- ABI (Application Binary Interface) Names  
- Typical calling-convention roles

---

### 🗂️ Register Table

| Register | ABI Name | Description                                | Calling Convention Role |
|----------|----------|--------------------------------------------|--------------------------|
| x0       | zero     | Hard-wired zero                            | Immutable constant zero  |
| x1       | ra       | Return address                             | Caller-saved             |
| x2       | sp       | Stack pointer                              | Callee-saved             |
| x3       | gp       | Global pointer                             | Unallocatable            |
| x4       | tp       | Thread pointer                             | Unallocatable            |
| x5       | t0       | Temporary register 0                       | Caller-saved             |
| x6       | t1       | Temporary register 1                       | Caller-saved             |
| x7       | t2       | Temporary register 2                       | Caller-saved             |
| x8       | s0/fp    | Saved register 0 / Frame pointer           | Callee-saved             |
| x9       | s1       | Saved register 1                           | Callee-saved             |
| x10      | a0       | Function argument 0 / Return value 0       | Caller-saved             |
| x11      | a1       | Function argument 1 / Return value 1       | Caller-saved             |
| x12      | a2       | Function argument 2                        | Caller-saved             |
| x13      | a3       | Function argument 3                        | Caller-saved             |
| x14      | a4       | Function argument 4                        | Caller-saved             |
| x15      | a5       | Function argument 5                        | Caller-saved             |
| x16      | a6       | Function argument 6                        | Caller-saved             |
| x17      | a7       | Function argument 7                        | Caller-saved             |
| x18      | s2       | Saved register 2                           | Callee-saved             |
| x19      | s3       | Saved register 3                           | Callee-saved             |
| x20      | s4       | Saved register 4                           | Callee-saved             |
| x21      | s5       | Saved register 5                           | Callee-saved             |
| x22      | s6       | Saved register 6                           | Callee-saved             |
| x23      | s7       | Saved register 7                           | Callee-saved             |
| x24      | s8       | Saved register 8                           | Callee-saved             |
| x25      | s9       | Saved register 9                           | Callee-saved             |
| x26      | s10      | Saved register 10                          | Callee-saved             |
| x27      | s11      | Saved register 11                          | Callee-saved             |
| x28      | t3       | Temporary register 3                       | Caller-saved             |
| x29      | t4       | Temporary register 4                       | Caller-saved             |
| x30      | t5       | Temporary register 5                       | Caller-saved             |
| x31      | t6       | Temporary register 6                       | Caller-saved             |
