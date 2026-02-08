# 2.2.8  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.4.6.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.2.8 Be able to use variables and constants

This section covers the application of variables and constants to store, reuse and control values during program execution in digital software development.

## Using variables

### Features / Characteristics / Role

Variables are used to hold values that may change while a program runs. They support program logic by storing input data, intermediate results and outputs that can be updated as conditions change.

### Benefits

- enables dynamic handling of data  
- supports calculations and logical operations  
- allows programs to respond to changing inputs  
- improves readability through meaningful naming  
- supports reuse of values across a solution  

### Drawbacks

- incorrect updates can introduce logic errors  
- excessive variables increase complexity  
- poor naming reduces code clarity  
- improper initialisation may cause runtime errors  

---

## Using constants

### Features / Characteristics / Role

Constants are used to store fixed values that must not change during program execution. They provide reference values that remain consistent across a solution.

### Benefits

- prevents accidental modification of fixed values  
- improves readability by replacing hard-coded values  
- supports maintainability by centralising key values  
- reduces risk of inconsistencies  

### Drawbacks

- requires upfront identification of fixed values  
- excessive constants may clutter code  
- inappropriate use may reduce flexibility  

---

## Judgement

Suitability depends on:

i. whether values need to change during execution  
ii. clarity of naming and organisation  
iii. complexity of the solution  
iv. maintainability requirements  
v. developer experience  

Variables are suitable where values must change, while constants are suitable for fixed reference values. Effective use supports clarity and reliability, but poor management increases complexity and error risk.

---

!!! tip "Exam tip"
    Marks are awarded for linking variables and constants to program behaviour. Avoid stating that they “store values” without explaining how changing or fixed values affect logic, reliability and suitability.
