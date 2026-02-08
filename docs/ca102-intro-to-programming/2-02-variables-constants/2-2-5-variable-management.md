# 2.2.5  


![New Content](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.4.5.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.2.5 Know and understand how variables are managed by scope

This section covers how scope controls the visibility and lifetime of variables, including the use of global and local variables in digital software development.

## Global variables

### Features / Characteristics / Role

Global variables are declared outside functions or procedures and are accessible throughout the entire program. They retain their values for the duration of program execution and can be read or modified by multiple parts of a solution.

### Benefits

- enables shared access to common values  
- supports coordination between different program components  
- simplifies data availability across functions  

### Drawbacks

- increases risk of unintended modification  
- makes debugging more difficult  
- reduces code readability  
- can introduce hidden dependencies between components  

---

## Local variables

### Features / Characteristics / Role

Local variables are declared within functions or procedures and are accessible only within that defined scope. Their lifetime is limited to the execution of that block of code.

### Benefits

- improves encapsulation of data  
- reduces risk of unintended interactions  
- supports modular and maintainable code  
- simplifies debugging by limiting variable visibility  

### Drawbacks

- values are not accessible outside their scope  
- may require passing data between functions  
- repeated declarations can increase development effort  

---

## Judgement

Suitability depends on:

i. need for shared access to data  
ii. complexity of the solution  
iii. risk of unintended side effects  
iv. maintainability requirements  
v. developer experience  

Global variables may be suitable where common values must be accessed widely, while local variables are more suitable for maintaining control and reducing unintended interactions within modular solutions.

---

!!! tip "Exam tip"
    Marks are awarded for comparing global and local scope. Avoid listing definitions alone — explain how scope affects accessibility, reliability and suitability.
