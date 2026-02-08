# 2.7.5  


![New Content](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.7  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.7.5 Be able to interpret code using user-written and pre-written code

This section covers how user-written and pre-written functions and procedures are interpreted to understand program behaviour and data flow in digital software development.

## Interpreting user-written functions and procedures

### Features / Characteristics / Role

User-written functions and procedures are interpreted by examining their parameters, internal logic and outputs to understand how custom components contribute to overall program execution.

### Benefits

- supports understanding of bespoke solution logic  
- enables tracing of data through custom components  
- assists identification of logic errors  
- improves comprehension of program structure  

### Drawbacks

- quality of interpretation depends on code clarity  
- poorly written code reduces readability  
- requires understanding of developer-defined naming and structure  

---

## Interpreting pre-written functions and procedures

### Features / Characteristics / Role

Pre-written functions and procedures are interpreted by reviewing how they are called and how their returned values or actions affect program flow.

### Benefits

- enables understanding of how built-in or library code supports solutions  
- supports tracing of values through standard functionality  
- reduces need to analyse internal implementation  

### Drawbacks

- internal behaviour may be hidden  
- relies on external documentation  
- misuse can be difficult to detect  

---

## Interpreting combined user-written and pre-written code

### Features / Characteristics / Role

Interpreting both custom and library code together allows full tracing of execution paths and data movement across a solution.

### Benefits

- supports end-to-end understanding of program behaviour  
- enables identification of integration issues  
- improves accuracy when analysing outputs  
- assists debugging  

### Drawbacks

- complexity increases with multiple dependencies  
- requires understanding of both custom logic and external functions  

---

## Judgement

Suitability depends on:

i. clarity of code structure  
ii. quality of naming conventions  
iii. reliance on external libraries  
iv. complexity of program logic  
v. developer experience  

Interpreting code using user-written and pre-written components is suitable for understanding program behaviour and identifying faults, but becomes more difficult as complexity and external dependencies increase.

---

!!! tip "Exam tip"
    Marks are awarded for tracing execution through both custom and pre-written components. Avoid treating functions and procedures separately — explain how values flow between user-written and library code.
