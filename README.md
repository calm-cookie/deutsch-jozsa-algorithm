# Deutsch Jozsa Algorithm

_Implementation of Deutsch-Jozsa Algorithm using Qiskit._

Deutsch Jozsa Algorithm is **quantum algorithm** used to solve a simple problem in a **single step**. 

The problem takes **2<sup>N</sup> - 1 steps** to solve classically.

### The problem

There is a function that takes a **n-bit string** as input and gives either **0 or 1** as output. The function is either **constant** or **balanced**.
- **Balanced**:  The function outputs **1 for half of the inputs** and **0 for the other half of the inputs**.
- **Constant**: The function outputs either **1 or 0 for all the inputs**.

**The problem is to find whether the function is constant or balanced.**
