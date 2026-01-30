# 2.2.4–2.2.6 Scope

---

## 2.2.4 Definition and Purpose of Scope
**Scope** defines where a variable can be accessed and used within a program.  
It controls:
- the visibility of variables
- the lifetime of variables
- where values can be read or changed

Scope helps manage complexity and prevents unintended interactions between parts of a program.

---

## 2.2.5 Management of Variables by Scope

Variables are managed according to where they are declared.

---

### Global Variables
- Declared **outside** of functions or procedures
- Accessible throughout the program

**Characteristics:**
- Can be read from any part of the program
- Can be modified by multiple sections of code

**Considerations:**
- Useful for values needed across the whole program
- Can increase risk of unintended changes

---

### Local Variables
- Declared **inside** a function or procedure
- Accessible **only within** that function or procedure

**Characteristics:**
- Exist only while the function or procedure is executing
- Cannot be accessed from outside their scope

**Considerations:**
- Reduce risk of conflicts between variables
- Improve clarity and maintainability

---

## 2.2.6 Using Scope

Using scope correctly involves:
- selecting appropriate variable locations
- limiting access to where it is required
- avoiding unnecessary global variables

Correct use of scope:
- improves reliability of programs
- supports structured and modular code
- reduces logical errors

Incorrect use of scope can lead to:
- unexpected changes to values
- difficulty tracing errors
- reduced readability

---

## Exam Focus
You should be able to:
- Define scope
- Distinguish between global and local variables
- Explain how scope affects variable access and behaviour
- Use scope appropriately in a given scenario

!!! tip "Exam tip"
Marks are often awarded for **explaining how scope controls access to variables**, not just stating where a variable is declared.
