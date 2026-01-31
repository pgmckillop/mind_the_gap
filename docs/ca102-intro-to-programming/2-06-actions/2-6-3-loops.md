## 2.6 Actions

### 2.6.3 Loops
Loops are control structures that allow a block of code to be executed repeatedly.  
The purpose of loops is to automate repetition and reduce the need for duplicated code.  
Loops are used when the same set of instructions must be executed multiple times.

- **Count-controlled loop**  
  A loop that repeats a fixed number of times.  
  **Purpose:** to perform repetition when the number of iterations is known in advance.  
  **Benefits:**  
  - predictable number of repetitions  
  - clear control over execution  
  - efficient for processing fixed-size data sets  
  **Drawbacks:**  
  - not suitable when the number of repetitions cannot be predetermined  
  - may require additional logic if conditions change during execution.

- **Condition-controlled loop**  
  A loop that repeats while a condition remains true.  
  **Purpose:** to perform repetition when the number of iterations depends on a condition evaluated at runtime.  
  **Benefits:**  
  - flexible control based on changing conditions  
  - suitable for uncertain or variable repetition counts  
  **Drawbacks:**  
  - risk of infinite loops if conditions are not managed correctly  
  - less predictable execution length.

### 2.6.4 Iteration
Iteration is the repeated execution of a set of instructions using a loop structure.

- **Count-controlled `for` loops**  
  Iterate over a fixed range or sequence.  
  **Purpose:** to implement count-controlled iteration clearly and concisely.  
  **Benefits:**  
  - clear start and end points  
  - improved readability for fixed iterations  
  - reduced risk of infinite loops  
  **Drawbacks:**  
  - limited flexibility for changing conditions  
  - unsuitable when iteration count is unknown.

- **Condition-controlled `while do` loops**  
  Iterate while a specified condition evaluates to true.  
  **Purpose:** to implement condition-controlled iteration based on runtime evaluation.  
  **Benefits:**  
  - adaptable to changing conditions  
  - suitable for input validation and event-driven repetition  
  **Drawbacks:**  
  - increased risk of infinite loops  
  - requires careful condition management.

## Exam Focus
You should be able to:
- Explain the purpose of loops
- Distinguish between count-controlled and condition-controlled loops
- Explain iteration and how it is implemented
- Compare `for` loops and `while do` loops
- Justify the suitability of a loop type for a given context

!!! tip "Exam tip"
    Questions may require comparison or judgement of loop types. Responses should weigh predictability, flexibility and risk, justifying loop selection based on whether the number of iterations is known or condition-dependent.
