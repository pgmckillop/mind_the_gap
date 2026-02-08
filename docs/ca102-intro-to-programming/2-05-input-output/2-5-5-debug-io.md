# 2.5.5


![retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.5.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.5.5 Be able to debug code using input and output

This section covers how input and output are used during debugging to identify, locate and correct errors in digital software solutions.

## Debugging using input

### Features / Characteristics / Role

Input is used during debugging to test different values and conditions. Debugging with input involves examining how data enters a program and how variations in input affect processing and outcomes.

### Benefits

- helps identify errors caused by unexpected or invalid input  
- supports testing of different execution paths  
- enables verification of variable values at key stages  
- assists isolation of logic errors  

### Drawbacks

- requires carefully chosen test values  
- unclear input handling can hide faults  
- depends on meaningful variable naming  

---

## Debugging using output

### Features / Characteristics / Role

Output is used to display intermediate or final values so program behaviour can be observed. Debugging with output involves inserting or reviewing output statements to trace data flow and logic.

### Benefits

- reveals internal program state  
- supports tracking of value changes  
- assists identification of incorrect calculations or decisions  
- improves understanding of execution flow  

### Drawbacks

- excessive output reduces clarity  
- temporary debugging output must be removed  
- poorly formatted output can mislead interpretation  

---

## Debugging using combined input and output

### Features / Characteristics / Role

Using input and output together allows values to be traced from entry through processing to result, supporting systematic identification of faults.

### Benefits

- enables end-to-end verification of program behaviour  
- supports identification of data flow errors  
- improves accuracy of fault location  
- assists confirmation of corrections  

### Drawbacks

- complex programs may require extensive tracing  
- relies on clear program structure  

---

## Judgement

Suitability depends on:

i. complexity of the solution  
ii. quality of input data  
iii. clarity of output statements  
iv. structure of program logic  
v. developer experience  

Debugging using input and output is suitable for tracing data flow and identifying logic errors, but becomes less effective where outputs are unclear or program structure is poor.

---

!!! tip "Exam tip"
Marks are awarded for explaining how input and output reveal errors. Avoid stating that values are “printed” — link debugging output to tracing data flow, locating faults and confirming fixes.
