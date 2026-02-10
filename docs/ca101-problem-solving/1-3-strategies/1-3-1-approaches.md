# 1.3.1  

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 1.2  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

## 1.3.1 Know the different approaches to solving problems and understand their purpose and when they are used

This section covers the main approaches to problem solving in digital software development and explains their purpose and typical use.

## Top-down approach

### Features / Characteristics / Role

The top-down approach starts with the overall problem or system and progressively breaks it down into smaller components until each part can be implemented.

### Benefits

- provides a clear high-level view of the solution  
- supports structured planning and design  
- helps identify system-wide requirements early  
- improves coordination between components  

### Drawbacks

- detailed implementation issues may be identified late  
- requires accurate initial understanding of requirements  
- changes at higher levels can impact multiple components  

---

## Bottom-up approach

### Features / Characteristics / Role

The bottom-up approach begins by developing individual components and combining them to form a complete solution.

### Benefits

- enables early development and testing of components  
- supports reuse of existing modules  
- allows flexibility in assembling solutions  
- reduces dependency on full system design at early stages  

### Drawbacks

- may lack overall system structure  
- integration issues can emerge late  
- can lead to mismatched components without clear coordination  

---

## Modularisation

### Features / Characteristics / Role

Modularisation structures solutions into independent, self-contained modules that interact through defined interfaces.

### Benefits

- improves maintainability and scalability  
- supports parallel development  
- enables reuse of components  
- simplifies testing and debugging  

### Drawbacks

- requires careful design of module boundaries  
- introduces coordination and integration overhead  
- may increase initial design effort  

---

## Judgement

Suitability depends on:

i. complexity and scale of the problem  
ii. clarity of overall requirements  
iii. availability of reusable components  
iv. time and resource constraints  
v. developer experience  

Top-down approaches support structured system design, bottom-up approaches support component-led development, and modularisation supports maintainable and scalable solutions. Selection depends on project constraints and development priorities.

---

!!! tip "Exam tip"
    Marks are awarded for linking each approach to its purpose and suitability. Avoid listing top-down, bottom-up and modularisation without explaining how each affects structure, development and integration.
