# 2.9.4  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.8  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.9.4 Determine the order of actions

This section covers how the order of actions is determined to improve execution efficiency and memory usage in digital software development.

## Ordering actions within processes

### Features / Characteristics / Role

Determining the order of actions involves arranging program steps so operations occur in a sequence that minimises processing time and memory consumption. This controls when data is created, used and discarded during execution.

It is used to:

- reduce unnecessary processing  
- minimise repeated operations  
- control when values are stored or released  
- improve overall program performance  

### Benefits

- improves execution time  
- reduces memory usage  
- supports predictable program behaviour  
- improves scalability of solutions  
- assists maintainability through structured flow  

### Drawbacks

- requires detailed understanding of program logic  
- optimisation may reduce code readability  
- changes to action order can affect program outcomes  
- increases design complexity  

---

## Ensuring efficiency of execution time

### Features / Characteristics / Role

Ordering actions so prerequisite steps occur first prevents wasted processing and avoids repeating calculations.

### Benefits

- reduces runtime delays  
- supports responsive systems  
- improves throughput of processes  

### Drawbacks

- performance tuning increases development effort  

---

## Ensuring efficient use of memory

### Features / Characteristics /Role

Action order controls when variables and data structures are created and discarded, affecting memory consumption during execution.

### Benefits

- minimises peak memory usage  
- supports operation on constrained systems  
- improves scalability  

### Drawbacks

- memory optimisation may restrict flexibility  

---

## Judgement

Suitability depends on:

i. complexity of program logic  
ii. number of dependent actions  
iii. performance requirements  
iv. available memory resources  
v. developer experience  

Determining the order of actions is suitable for improving performance and resource use, but increases design complexity and may reduce readability.

---

!!! tip "Exam tip"
Marks are awarded for linking action order to execution time and memory use. Avoid stating that steps are “optimised” — explain how ordering reduces processing and resource consumption.
