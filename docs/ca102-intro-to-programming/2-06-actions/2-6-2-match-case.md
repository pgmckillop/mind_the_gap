# 2.6.2 Selection: `match / case`

---

## Purpose of `match / case`
`match / case` is a **selection structure** used to choose between **multiple possible paths** based on the value of an expression.

It is used when:
- there are **several discrete options**
- each option leads to a **different action**
- clarity is required when handling many conditions

---

## How `match / case` Works
- An expression is evaluated once using `match`
- The value is compared against multiple `case` options
- The first matching `case` is executed
- A **default case** can be included using `_`

---

## Basic Structure

```python
match value:
    case option1:
        # action
    case option2:
        # action
    case _:
        # default action


## Key Points
- each `case` represents a possible outcome  
- `_` acts as a catch-all if no other case matches  
- only one `case` is executed  

---

## Example: Menu Selection

```python
choice = input("Enter A, B, or C: ")

match choice:
    case "A":
        print("Option A selected")
    case "B":
        print("Option B selected")
    case "C":
        print("Option C selected")
    case _:
        print("Invalid option")


## What This Demonstrates
- selection based on user input  
- clear handling of multiple fixed options  
- a default outcome for invalid input  

---

## Comparison with Other Selection Methods

`match / case` is most suitable when:
- there are many specific values to test  
- each value has a distinct outcome  
- readability is important  

It avoids long chains of `if / elif / else` statements.

---

## Correct Use of `match / case`

Using `match / case` correctly involves:
- matching against clear, known values  
- including a default case where appropriate  
- ensuring each case performs a distinct action  

Incorrect use may lead to:
- unreachable cases  
- unclear logic  
- missing outcomes  

---

## Exam Focus
You should be able to:
- explain the purpose of `match / case`  
- identify when `match / case` is more suitable than other selection methods  
- interpret and create simple `match / case` structures  

!!! tip "Exam tip"
Marks are often awarded for **justifying why `match / case` is appropriate** when handling multiple discrete options.
