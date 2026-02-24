# 1.2.11

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in topics of the old specification.  
Be careful! The focus is a bit different in this specification.  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

## 1.2.11 Translating between different notations for algorithms

Translating between algorithm notations involves converting logic expressed in one form (such as flowcharts, written descriptions or code) into another while preserving sequence, selection, iteration and outcomes. :contentReference[oaicite:0]{index=0}

The following strategies support accurate translation:

**Identify inputs, processing and outputs first**  
  Extract what data enters the algorithm, what operations occur, and what results are produced.  
  **Purpose:** to establish the core structure before translation.  
  **Benefits:**  
  - preserves algorithm intent  
  - reduces risk of missing steps  
  **Drawbacks:**  
  - does not expose control flow on its own.

**Map sequence directly**  
  Convert ordered steps one-for-one into the new notation.  
  **Purpose:** to maintain execution order.  
  **Benefits:**  
  - prevents reordering errors  
  - supports logical consistency  
  **Drawbacks:**  
  - lengthy algorithms require careful attention.

**Convert selection explicitly**  
  Translate decisions into equivalent conditional structures.  
  **Purpose:** to preserve branching logic.  
  **Benefits:**  
  - ensures alternative paths remain intact  
  - maintains correctness of outcomes  
  **Drawbacks:**  
  - nested decisions increase complexity.

**Translate iteration carefully**  
  Identify loops and recreate them using appropriate constructs.  
  **Purpose:** to maintain repetition behaviour.  
  **Benefits:**  
  - preserves loop conditions and limits  
  - prevents infinite or missing iterations  
  **Drawbacks:**  
  - loop boundaries are easy to misinterpret.

**Match symbols to constructs**  
  Convert flowchart symbols or hierarchical markers into equivalent written or coded forms.  
  **Purpose:** to ensure representation consistency.  
  **Benefits:**  
  - reduces ambiguity  
  - supports accurate conversion  
  **Drawbacks:**  
  - requires familiarity with all notation types.

**Preserve variable names and roles**  
  Keep identifiers consistent across representations.  
  **Purpose:** to avoid confusion and logic errors.  
  **Benefits:**  
  - improves traceability  
  - simplifies verification  
  **Drawbacks:**  
  - may require renaming to fit coding conventions.

**Verify by tracing after translation**  
  Step through the translated algorithm using sample inputs.  
  **Purpose:** to confirm behaviour matches the original.  
  **Benefits:**  
  - validates correctness  
  - exposes translation mistakes  
  **Drawbacks:**  
  - time-consuming.

## Exam Focus
You should be able to:
- Convert algorithms between flowcharts, written descriptions and code
- Preserve sequence, selection and iteration
- Maintain correct inputs and outputs
- Verify translated algorithms by tracing
- Explain how different representations express the same logic

!!! tip "Exam tip"
    When translating algorithms, marks are awarded for preserving logic rather than syntax alone. Always ensure that decision paths, loops and outputs behave identically in the new notation.