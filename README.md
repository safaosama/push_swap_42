# Push_Swap

A pair programming project from the **42 Common Core** focused on sorting data efficiently using a restricted set of stack operations.

---

## Overview

Push_Swap is an algorithmic challenge that requires sorting a stack of integers using two stacks and a limited set of predefined operations.

The goal is to sort the data with the **fewest possible instructions**, requiring efficient algorithm design, optimization, and careful complexity analysis.

This project explores low-level problem solving, stack manipulation, and performance-oriented algorithm implementation under strict constraints.

---

## Project Objectives

- Design efficient sorting algorithms
- Minimize the number of executed operations
- Analyze algorithmic complexity
- Optimize stack manipulation strategies
- Strengthen collaborative problem-solving skills

---

## Allowed Operations

### Swap
- `sa` → swap first two elements of stack A
- `sb` → swap first two elements of stack B
- `ss` → execute `sa` and `sb`

### Push
- `pa` → push top element from B to A
- `pb` → push top element from A to B

### Rotate
- `ra` → shift stack A up by one
- `rb` → shift stack B up by one
- `rr` → execute `ra` and `rb`

### Reverse Rotate
- `rra` → shift stack A down by one
- `rrb` → shift stack B down by one
- `rrr` → execute `rra` and `rrb`

---

## Compilation

```bash
make
```

---

## Usage

```bash
./push_swap 4 67 3 87 23
```

Example output:

```bash
pb
ra
sa
pa
```

---

## Constraints

The program must:

- Use only the allowed operations
- Produce the smallest possible instruction count
- Handle invalid input safely
- Detect duplicate values
- Parse arguments correctly
- Optimize execution performance

---

## Sorting Strategy

The implementation may include:

- Small-set optimized sorting
- Chunk-based sorting
- Cost-based movement calculation
- Rotation minimization
- Stack position optimization

---

## Collaboration

This project was developed as a **pair programming project** as part of the **42 Common Core** curriculum.

Collaboration included:

- Algorithm design
- Code implementation
- Optimization and testing
- Debugging and performance analysis
- Code review and refinement

---

## Contributors

- Safa Osama
- Noor ELali

---

## Learning Outcomes

Through this project, we developed practical experience in:

- Algorithm optimization
- Stack-based data structures
- Complexity analysis
- Performance-focused programming
- Collaborative software development

---

## 42 Common Core Project

This project is part of the **42 School Common Core**, designed to strengthen algorithmic thinking and efficient software engineering practices through constrained problem-solving.
