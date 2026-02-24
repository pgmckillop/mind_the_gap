# 1.2.8

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in topics of the old specification.  
Be careful! The focus is a bit different in this specification.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

## 1.2.8 Determining the output of an algorithm given an input

To determine the output of an algorithm when provided with specific input values, systematic tracing and logical reasoning are used to follow how data moves and changes throughout the algorithm.

---

**Substitute the given input values first**

Replace variables or input placeholders with the provided values.

**Purpose:**  
to establish a concrete starting point.

**Benefits:**

- removes ambiguity  
- simplifies tracing  

**Drawbacks:**

- errors at this stage affect all later steps.

---

**Execute steps in order (sequence)**

Follow instructions line by line.

**Purpose:**  
to maintain correct execution flow.

**Benefits:**

- prevents skipped operations  
- ensures logical progression  

**Drawbacks:**

- slow for long algorithms.

---

**Evaluate conditions carefully (selection)**

Check each condition using current values.

**Purpose:**  
to determine which branches execute.

**Benefits:**

- clarifies decision paths  
- avoids incorrect assumptions  

**Drawbacks:**

- nested conditions increase complexity.

---

**Repeat loops accurately (iteration)**

Count iterations or monitor loop conditions.

**Purpose:**  
to ensure repeated steps are applied correctly.

**Benefits:**

- avoids under- or over-execution  
- confirms termination  

**Drawbacks:**

- easy to lose track of loop counters.

---

**Update variables at every change**

Record new values immediately.

**Purpose:**  
to track evolving state.

**Benefits:**

- exposes logic clearly  
- prevents stale values  

**Drawbacks:**

- requires careful organisation.

---

**Use trace tables or written walkthroughs**

Record each step, variable value and output.

**Purpose:**  
to visualise execution.

**Benefits:**

- reduces mistakes  
- improves confidence in answers  

**Drawbacks:**

- time-consuming for complex algorithms.

---

**Confirm final output explicitly**

Identify what is printed, returned or produced.

**Purpose:**  
to distinguish intermediate values from final results.

**Benefits:**

- ensures correct answer focus  
- avoids reporting temporary values  

**Drawbacks:**

- requires attention to output statements.

---

## Exam Focus  

You should be able to:

- Substitute input values correctly
- Trace sequence, selection and iteration
- Track variable changes accurately
- Use trace tables or step-through methods
- Identify the final output produced

!!! tip "Exam tip"
    When asked to determine algorithm output, always trace step by step using the given input. Credit is awarded for correct logical progression, not guessing. Ensure the final value reported is the actual output, not an intermediate calculation.