## 2.6 Actions

### 2.6.2 Selection
Selection is used to control the flow of a program by choosing between alternative actions based on conditions.  
The purpose of selection is to allow different outcomes or paths of execution depending on data values or conditions encountered during program execution.  
Selection is used when decisions must be made within a program. :contentReference[oaicite:0]{index=0}

- **if**  
  Evaluates a condition and executes a block of code when the condition is true.  
  **Purpose:** to perform an action only when a specific condition is met.  
  **Benefits:**  
  - supports simple decision making  
  - improves control over program flow  
  **Drawbacks:**  
  - limited to a single condition  
  - may require additional structures for multiple outcomes.

- **else if**  
  Evaluates an additional condition when a previous condition is false.  
  **Purpose:** to support multiple conditional paths within a decision structure.  
  **Benefits:**  
  - enables handling of multiple conditions  
  - improves clarity when conditions are mutually exclusive  
  **Drawbacks:**  
  - can reduce readability if many conditions are chained  
  - may increase complexity.

- **else**  
  Executes a block of code when all preceding conditions are false.  
  **Purpose:** to provide a default outcome when no conditions are met.  
  **Benefits:**  
  - ensures all possible cases are handled  
  - improves robustness of decision logic  
  **Drawbacks:**  
  - may mask logic errors if used inappropriately  
  - may reduce clarity if default behaviour is not clearly defined.

- **match/case**  
  Compares a value against multiple possible patterns and executes the matching case.  
  **Purpose:** to provide a structured and readable approach to selection when comparing a single value against several possible outcomes.  
  **Benefits:**  
  - improves readability compared to long chains of conditional statements  
  - clearly separates each possible outcome  
  - supports structured decision making  
  **Drawbacks:**  
  - limited to specific matching patterns  
  - may be unnecessary for simple decision structures.

### Example of match/case

```python
status_code = 404

match status_code:
    case 200:
        message = "OK"
    case 400:
        message = "Bad Request"
    case 401:
        message = "Unauthorised"
    case 404:
        message = "Not Found"
    case 500:
        message = "Server Error"
    case _:
        message = "Unknown Status"




## Exam Focus
You should be able to:
- Explain the purpose of selection
- Identify when selection is used
- Distinguish between if, else if, else and match/case
- Compare benefits and drawbacks of different selection structures
- Justify the suitability of match/case compared to alternative selection methods

!!! tip "Exam tip"
    Questions may require justification of a selection structure. Responses should compare alternatives, weighing readability, complexity and suitability of decision logic, particularly when selecting between conditional chains and match/case.
