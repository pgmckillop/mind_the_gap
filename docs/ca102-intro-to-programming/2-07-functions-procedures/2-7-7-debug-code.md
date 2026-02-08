# 2.7.7  


![New Content](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.7  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.7.7 Be able to debug code using user-written and pre-written code

This section covers debugging techniques applied to both user-written and pre-written functions and procedures to identify and correct errors in digital software solutions.

## Debugging user-written functions and procedures

### Features / Characteristics / Role

Debugging user-written functions and procedures involves examining parameters, internal logic and outputs to locate faults within custom code components.

### Benefits

- enables identification of logic and implementation errors  
- supports tracing of values through custom routines  
- improves reliability of bespoke solution components  
- assists validation of expected behaviour  

### Drawbacks

- quality of debugging depends on code clarity  
- poorly structured code increases fault-finding time  
- errors may affect multiple parts of a solution  

---

## Debugging pre-written functions and procedures

### Features / Characteristics / Role

Debugging pre-written functions and procedures focuses on how library components are called and how returned values or actions affect program flow.

### Benefits

- enables verification of correct usage of library features  
- supports identification of incorrect parameters or assumptions  
- reduces need to inspect internal implementation  

### Drawbacks

- internal behaviour is not directly visible  
- relies on external documentation  
- faults may originate outside developer control  

---

## Debugging combined user-written and pre-written code

### Features / Characteristics / Role

Debugging both custom and library code together allows tracing of execution paths across the entire solution to identify integration issues.

### Benefits

- supports end-to-end fault identification  
- improves accuracy when isolating errors  
- assists confirmation of corrections  
- enhances overall solution reliability  

### Drawbacks

- increased complexity with multiple dependencies  
- requires understanding of both custom logic and external components  

---

## Judgement

Suitability depends on:

i. clarity of code structure  
ii. reliance on external libraries  
iii. complexity of program logic  
iv. quality of documentation  
v. developer experience  

Debugging user-written and pre-written functions and procedures is suitable for locating logic and integration errors, but becomes more challenging as complexity and dependency levels increase.

---

!!! tip "Exam tip"
    Marks are awarded for explaining how faults are located across custom and library code. Avoid stating that code is “debugged” — link debugging actions to tracing values, checking parameters and confirming fixes.
