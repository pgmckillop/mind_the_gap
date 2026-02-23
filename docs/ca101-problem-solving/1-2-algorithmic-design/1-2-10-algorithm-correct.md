# 1.2.10

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 1.2.  
Be careful! The focus is a bit different in this specification.
If you have access to the textbooks, you can use those resources to enhance your understanding.

## 1.2.10 Correcting errors in an algorithm

To correct errors in an algorithm, students should apply structured debugging techniques to modify sequence, selection, iteration or data handling so that the algorithm produces the intended output and behaves correctly. :contentReference[oaicite:0]{index=0}

The following strategies support effective correction:

**Confirm the intended outcome first**  
  Restate what the algorithm should achieve.  
  **Purpose:** to ensure corrections align with the required behaviour.  
  **Benefits:**  
  - prevents fixing the wrong problem  
  - clarifies success criteria  
  **Drawbacks:**  
  - may require revisiting the original requirements.

**Correct input handling**  
  Adjust how inputs are read or assigned.  
  **Purpose:** to ensure correct starting values.  
  **Benefits:**  
  - resolves errors caused by incorrect initial data  
  - improves reliability  
  **Drawbacks:**  
  - may not address internal logic faults.

**Fix sequence errors**  
  Reorder steps so instructions execute in the correct order.  
  **Purpose:** to restore logical flow.  
  **Benefits:**  
  - resolves dependency issues  
  - improves clarity  
  **Drawbacks:**  
  - incorrect reordering can introduce new faults.

**Amend selection conditions**  
  Modify conditional expressions or branches.  
  **Purpose:** to ensure correct decision paths are taken.  
  **Benefits:**  
  - resolves incorrect branching  
  - ensures all required cases are handled  
  **Drawbacks:**  
  - complex conditions are easy to misjudge.

**Repair iteration logic**  
  Adjust loop conditions, counters or updates.  
  **Purpose:** to prevent infinite loops or incorrect repetition.  
  **Benefits:**  
  - restores correct loop behaviour  
  - improves termination reliability  
  **Drawbacks:**  
  - small mistakes can reintroduce looping errors.

**Correct variable updates and calculations**  
  Modify assignments or arithmetic operations.  
  **Purpose:** to ensure values change as intended.  
  **Benefits:**  
  - resolves incorrect outputs  
  - improves accuracy  
  **Drawbacks:**  
  - requires careful tracing of value changes.

**Retest after each change**  
  Re-run the algorithm with known inputs.  
  **Purpose:** to confirm that corrections are effective.  
  **Benefits:**  
  - validates fixes  
  - prevents regression  
  **Drawbacks:**  
  - increases time spent debugging.

**Use trace tables or walkthroughs again**  
  Re-trace execution after corrections.  
  **Purpose:** to verify behaviour step by step.  
  **Benefits:**  
  - confirms correctness  
  - exposes remaining issues  
  **Drawbacks:**  
  - time-consuming.

## Exam Focus
You should be able to:
- Modify algorithms to correct logical errors
- Fix sequence, selection and iteration faults
- Correct variable and calculation mistakes
- Retest algorithms to confirm corrections
- Explain why a correction resolves a specific error

!!! tip "Exam tip"
    When correcting errors, always explain what was wrong and how your change fixes it. Marks are awarded for clear justification linked to control flow or value changes, not just providing a revised algorithm.