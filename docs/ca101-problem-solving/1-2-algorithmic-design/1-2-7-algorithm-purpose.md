# 1.2.7

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in topics of the old specification.  
Be careful! The focus is a bit different in this specification.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

## 1.2.7 Determining the purpose of an algorithm and how it works

To determine the purpose of an algorithm and understand how it works, structured analysis is used to identify inputs, processing steps and outputs, and to trace the flow of control through the algorithm.

---

**Identify inputs and outputs**

Determine what data enters the algorithm and what results are produced.

**Purpose:**  
to establish the overall function of the algorithm.

**Benefits:**

- clarifies intended outcome  
- provides context for internal steps  

**Drawbacks:**

- may not reveal internal logic on its own.

---

**Follow the sequence of steps**

Read each instruction in order, noting how data changes.

**Purpose:**  
to understand processing flow.

**Benefits:**

- supports step-by-step tracing  
- highlights dependencies between steps  

**Drawbacks:**

- time-consuming for longer algorithms.

---

**Locate selection and iteration**

Identify decision points and loops.

**Purpose:**  
to understand alternative paths and repetition.

**Benefits:**

- reveals control flow  
- highlights conditional behaviour  

**Drawbacks:**

- nested structures increase complexity.

---

**Track variable changes**

Observe how values are assigned and modified.

**Purpose:**  
to understand how results are produced.

**Benefits:**

- exposes logical intent  
- supports error detection  

**Drawbacks:**

- requires careful attention.

---

**Use trace tables or manual walkthroughs**

Step through the algorithm using sample values.

**Purpose:**  
to visualise execution.

**Benefits:**

- confirms understanding  
- exposes unexpected behaviour  

**Drawbacks:**

- limited to small data sets.

---

**Summarise the algorithm in one sentence**

State what the algorithm achieves overall.

**Purpose:**  
to confirm comprehension of purpose.

**Benefits:**

- reinforces high-level understanding  
- supports concise explanation  

**Drawbacks:**

- may overlook implementation detail.

---

## Exam Focus  

You should be able to:

- Identify inputs, processing and outputs
- Trace algorithm execution step by step
- Recognise sequence, selection and iteration
- Explain how values change during execution
- State the overall purpose of an algorithm clearly

!!! tip "Exam tip"
    Questions may present an algorithm and require explanation of its purpose and behaviour. Responses should reference inputs, outputs and control flow, and describe how steps combine to achieve the final result rather than listing lines of code in isolation.