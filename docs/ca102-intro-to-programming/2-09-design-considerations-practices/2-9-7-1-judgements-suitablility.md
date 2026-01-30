# 2.9.7 Suitability of Programming Solutions

---

## What This Topic Is About
This topic focuses on **judging whether a programming solution is suitable** for a given problem.

It goes beyond *whether the code works* and considers:
- how appropriate the solution is
- whether it meets requirements
- whether it is the *best* choice in context

This topic is strongly **analytical and evaluative (AO3)**.

---

## What Makes a Solution Suitable?

A suitable solution is one that:
- Meets the **user and system requirements**
- Is **readable and maintainable**
- Is **efficient enough** for its purpose
- Is **robust** against incorrect input or errors
- Is appropriate for the **context and constraints**

---

## Key Factors to Consider When Judging Suitability

### Readability and Maintainability
- Clear variable and function names
- Consistent coding conventions
- Logical structure
- Appropriate use of comments

**Why this matters**
- Code is easier to understand, debug, and update
- Important in team-based development

---

### Efficiency
- Uses reasonable processing time
- Uses memory appropriately
- Avoids unnecessary repetition or complexity

**Why this matters**
- Inefficient solutions may work but perform poorly at scale

---

### Robustness
- Handles unexpected or invalid input
- Fails gracefully with clear error messages
- Avoids crashes or undefined behaviour

**Why this matters**
- Improves reliability and user trust

---

### Appropriateness of Constructs
- Correct choice of:
  - selection (`if`, `match`)
  - iteration (`for`, `while`)
  - functions or procedures
  - data structures

**Why this matters**
- Different constructs are better suited to different problems

---

## Comparative Judgement Examples

### Example 1 — Loop Choice
**Scenario:** Repeating a known number of times

- `for` loop → **more suitable**
- `while` loop → less suitable

**Judgement**
A `for` loop is clearer and less error-prone when the number of iterations is known.

---

### Example 2 — Selection Method
**Scenario:** Selecting from many fixed options

- `match / case` → **more suitable**
- Long `if / elif` chain → less suitable

**Judgement**
`match / case` improves readability and maintainability when handling multiple fixed values.

---

### Example 3 — Function Design
**Scenario:** Reusing a calculation in multiple places

- Function with a return value → **more suitable**
- Repeated inline code → less suitable

**Judgement**
Using a function improves modularity and reduces duplication.

---

## Making a Judgement (Exam Technique)

When asked to evaluate suitability, you should:
1. Identify the **problem requirements**
2. Describe the **solution used**
3. Judge how well it meets the requirements
4. Compare it with at least one alternative
5. Justify why it is **more or less suitable**

---

## Common Exam Pitfalls
- Describing code without evaluating it
- Saying a solution is “good” without justification
- Ignoring context such as scale, users, or constraints

---

## Exam Focus
You should be able to:
- Judge whether a programming solution is suitable
- Compare two possible solutions
- Justify decisions using clear reasoning
- Link suitability to context and requirements

!!! tip "Exam tip"
Higher-mark answers compare **alternatives** and clearly justify *why one solution is more suitable than another in context*.
