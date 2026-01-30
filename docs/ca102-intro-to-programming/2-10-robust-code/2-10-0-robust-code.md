# 2.10 Robust Code

---

## Purpose of Robust Code
**Robust code** is code that continues to operate correctly in a range of situations, including unexpected conditions.  
Robustness supports:
- reliable program behaviour
- predictable outputs
- safer operation when inputs or execution conditions are not as expected

---

## 2.10.1 Characteristics of Robust Code

Robust code:
- **handles unexpected inputs**
- **handles unexpected terminations**
- **produces specific and meaningful error messages**

**Why this matters**
- unexpected inputs can cause incorrect outputs or runtime errors  
- unexpected terminations can prevent correct completion of a process  
- meaningful error messages support effective fault identification and correction  

---

## 2.10.2 Debugging: Process and When It Is Used

**Debugging** is used when code does not behave as intended.

The debugging process involves:
- **locating errors in code**
- **correcting errors in code**

Debugging is required when:
- outputs are incorrect
- execution fails unexpectedly
- logic does not match the intended behaviour

---

## 2.10.3 Role of Debugging in Producing Robust Solutions

Debugging supports robust code by:
- identifying defects that cause failure or incorrect behaviour
- improving reliability of code under different conditions
- supporting the production of meaningful error behaviour

Robustness is improved when errors are found and corrected systematically.

---

## 2.10.4 Locating Errors in Code

Locating errors involves:
- identifying where code behaviour differs from what is expected
- tracing the flow of data and control through the program
- isolating the specific statement(s) responsible for the defect

The aim is to determine **what is wrong** and **where it occurs**.

---

## 2.10.5 Correcting Errors in Code

Correcting errors involves:
- changing code so it behaves as intended
- ensuring the correction addresses the cause of the defect
- confirming that outputs and behaviour are now correct

The aim is to ensure the solution runs reliably and produces expected results.

---

## Exam Focus
You should be able to:
- describe the characteristics of robust code
- explain the debugging process and when it is used
- explain the role of debugging in producing robust solutions
- locate errors in code
- correct errors in code

!!! tip "Exam tip"
Marks are often awarded for **linking robustness to handling unexpected situations and using debugging to locate and correct defects**, not just defining the terms.
