# 1.2.9

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 1.2.  
Be careful! The focus is a bit different in this specification.
If you have access to the textbooks, you can use those resources to enhance your understanding.

## 1.2.9 Identifying errors in an algorithm

To identify errors in an algorithm, students should apply systematic checking and logical reasoning to locate mistakes in sequence, selection, iteration or data handling. Errors may affect correctness, efficiency or termination of the algorithm. :contentReference[oaicite:0]{index=0}

The following strategies support error identification:

**Check inputs and outputs**  
  Verify that input values are used correctly and that outputs match expected results.  
  **Purpose:** to detect mismatches between intended and actual behaviour.  
  **Benefits:**  
  - highlights incorrect processing early  
  - confirms algorithm purpose alignment  
  **Drawbacks:**  
  - does not always reveal internal logic faults.

**Trace the algorithm step by step**  
  Walk through each instruction in order using sample data.  
  **Purpose:** to expose logical or calculation errors.  
  **Benefits:**  
  - reveals incorrect operations  
  - identifies unexpected value changes  
  **Drawbacks:**  
  - time-consuming for long algorithms.

**Inspect selection conditions**  
  Review all decision statements.  
  **Purpose:** to ensure conditions evaluate correctly and cover all required cases.  
  **Benefits:**  
  - exposes missing or incorrect branches  
  - prevents unintended default paths  
  **Drawbacks:**  
  - complex nested conditions are harder to verify.

**Check iteration logic**  
  Examine loop start values, conditions and updates.  
  **Purpose:** to detect infinite loops or incorrect repetition counts.  
  **Benefits:**  
  - identifies termination issues  
  - prevents skipped or repeated processing  
  **Drawbacks:**  
  - requires careful attention to counters or conditions.

**Track variable changes**  
  Monitor how variables are assigned and modified.  
  **Purpose:** to detect incorrect updates or misuse of values.  
  **Benefits:**  
  - exposes calculation and assignment errors  
  - supports accurate debugging  
  **Drawbacks:**  
  - can be difficult with many variables.

**Look for missing steps or incorrect order**  
  Review sequence logic.  
  **Purpose:** to ensure all required actions are present and correctly ordered.  
  **Benefits:**  
  - identifies incomplete algorithms  
  - improves logical flow  
  **Drawbacks:**  
  - subtle ordering errors may be overlooked.

**Use trace tables or walkthroughs**  
  Record each step and variable value.  
  **Purpose:** to visualise execution and isolate faults.  
  **Benefits:**  
  - systematic and reliable  
  - reduces guesswork  
  **Drawbacks:**  
  - increases workload.

## Exam Focus
You should be able to:
- Trace algorithms to locate errors
- Identify incorrect sequence, selection or iteration
- Detect variable and calculation mistakes
- Recognise missing or misplaced steps
- Explain why a given part of an algorithm is incorrect

!!! tip "Exam tip"
    When identifying errors, always justify your answer by referring to how values change or how control flow behaves. Marks are awarded for clear reasoning, not simply stating that an error exists.