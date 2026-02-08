# 2.8.4  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.8.x  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.8.4 Be able to debug code using validation

This section covers how validation logic is used during debugging to identify, locate and correct errors related to data entry and processing in digital software development.

## Debugging validation checks

### Features / Characteristics / Role

Debugging using validation involves examining validation rules and outcomes to determine why data is accepted or rejected. This includes tracing how input values interact with validation conditions and how failures affect program flow.

### Benefits

- supports identification of incorrect validation logic  
- enables tracing of input-related errors  
- assists verification of validation rules  
- improves reliability of data handling  

### Drawbacks

- complex validation structures can be difficult to analyse  
- unclear feedback obscures error sources  
- depends on quality of validation design  

---

## Debugging validation outcomes

### Features / Characteristics / Role

Validation outcomes are reviewed to confirm whether program behaviour matches expected results when valid or invalid data is supplied.

### Benefits

- clarifies control flow decisions  
- assists confirmation of corrective actions  
- supports end-to-end testing of data entry logic  

### Drawbacks

- multiple validation layers increase complexity  
- poor error reporting reduces effectiveness  

---

## Judgement

Suitability depends on:

i. clarity of validation rules  
ii. quality of error handling  
iii. complexity of program logic  
iv. volume of input data  
v. developer experience  

Debugging code using validation is suitable for locating data entry and logic faults, but becomes more challenging where validation structures are complex or poorly organised.

---

!!! tip "Exam tip"
Marks are awarded for explaining how validation reveals input errors. Avoid stating that validation is “checked” — link debugging actions to tracing values, locating faults and confirming fixes.
