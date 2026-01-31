## 2.7 Functions and procedures

### 2.7.1 Functions
Functions are reusable blocks of code that perform a specific task and return a result.  
Functions may or may not take parameters.  
Functions must return a result.  
The purpose of functions is to produce a value that can be used elsewhere in a program.  
Functions are used when a calculation or operation needs to return data to another part of the program. :contentReference[oaicite:0]{index=0}

**Benefits**
- support reuse of logic that produces a result  
- improve readability by encapsulating calculations or operations  
- support modular program structure.

**Drawbacks**
- inappropriate use may increase program complexity  
- returning results may be unnecessary when no value is required.

### 2.7.2 Procedures
Procedures are reusable blocks of code that perform a specific task without returning a result.  
Procedures may or may not take parameters.  
Procedures must not return a result.  
The purpose of procedures is to carry out actions within a program.  
Procedures are used when tasks need to be performed but no value needs to be returned. :contentReference[oaicite:1]{index=1}

**Benefits**
- improve structure by grouping actions  
- reduce duplication of code  
- improve maintainability.

**Drawbacks**
- cannot directly provide a result to other parts of the program  
- overuse may reduce clarity if responsibilities are not well defined.

## Exam Focus
You should be able to:
- Define functions and procedures
- Identify characteristics of functions and procedures
- Distinguish between returning and non-returning code blocks
- Explain when functions or procedures should be used
- Compare benefits and drawbacks of using functions and procedures

!!! tip "Exam tip"
    Questions may require comparison of functions and procedures. Responses should clearly distinguish return behaviour and justify suitability based on whether a result is required.

## Example

### Explain the purpose of this function and describe how it works

```python
def print_powers(number, limit):
    for power in range(1, limit + 1):
        print(number ** power)

```

## Example call
### print_powers(2, 5)

## Model Answer

The purpose of the function is to output successive powers of a given number.

The function takes two parameters. The first parameter represents the base number. The second parameter represents the highest power to which the base number will be raised.

A for loop is used to iterate through a sequence of values starting from 1 up to and including the value of the second parameter. On each iteration, the base number is raised to the current power using the exponentiation operator, and the result is printed to the screen.

The function does not return a value. Its purpose is to produce output to the screen rather than return data for further processing.


