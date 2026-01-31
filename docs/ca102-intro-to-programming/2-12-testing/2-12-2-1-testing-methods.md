## 2.12 Testing

### 2.12.2.1 Testing methods
Testing methods are structured approaches used to evaluate software solutions to identify defects, verify behaviour and assess suitability before deployment. Each method has a specific purpose and is used at different stages of development. :contentReference[oaicite:0]{index=0}

- **Concept testing**  
  Testing carried out to evaluate ideas or proposed solutions before development.  
  **Purpose:** to assess feasibility and suitability at an early stage.  
  **Benefits:**  
  - identifies unsuitable ideas early  
  - reduces wasted development effort  
  **Drawbacks:**  
  - limited detail available  
  - does not identify implementation defects.

- **Unit testing**  
  Testing of individual units or components in isolation.  
  **Purpose:** to verify that each unit functions correctly on its own.  
  **Benefits:**  
  - isolates faults to specific components  
  - simplifies debugging  
  **Drawbacks:**  
  - does not test interaction between components  
  - may miss system-level issues.

- **Boundary testing**  
  Testing data values at the limits of acceptable ranges.  
  **Purpose:** to identify errors at data boundaries.  
  **Benefits:**  
  - effective at detecting edge-case defects  
  - improves robustness  
  **Drawbacks:**  
  - limited coverage of internal logic  
  - relies on accurate identification of boundaries.

- **Integration testing**  
  Testing combined components after unit testing.  
  **Purpose:** to verify that components work together correctly.  
  **Benefits:**  
  - identifies interface and communication issues  
  - validates combined behaviour  
  **Drawbacks:**  
  - faults may be harder to trace  
  - requires completed components.

- **Performance testing**  
  Testing system behaviour under expected conditions.  
  **Purpose:** to assess speed, responsiveness and stability.  
  **Benefits:**  
  - identifies performance bottlenecks  
  - supports reliability assessment  
  **Drawbacks:**  
  - requires representative conditions  
  - may need specialised tools.

- **System testing**  
  Testing the complete system as a whole.  
  **Purpose:** to verify that the full solution meets requirements.  
  **Benefits:**  
  - validates end-to-end functionality  
  - identifies system-level issues  
  **Drawbacks:**  
  - faults may be costly to fix  
  - issues can be difficult to isolate.

- **Acceptance testing**  
  Testing carried out to confirm the solution meets user or business requirements.  
  **Purpose:** to determine readiness for release.  
  **Benefits:**  
  - confirms suitability for intended use  
  - supports formal approval  
  **Drawbacks:**  
  - issues found late in development  
  - limited focus on internal quality.

- **Usability testing**  
  Testing focused on ease of use and user interaction.  
  **Purpose:** to assess how effectively users can interact with the system.  
  **Benefits:**  
  - improves user experience  
  - identifies accessibility and interaction issues  
  **Drawbacks:**  
  - subjective results  
  - may require representative users.

- **Regression testing**  
  Testing performed after changes to ensure existing functionality still works.  
  **Purpose:** to detect unintended side effects of changes.  
  **Benefits:**  
  - maintains system stability  
  - protects existing functionality  
  **Drawbacks:**  
  - time-consuming  
  - may require automation for efficiency.

- **Load/stress testing**  
  Testing system behaviour under high or extreme demand.  
  **Purpose:** to assess reliability and limits of operation.  
  **Benefits:**  
  - identifies capacity limits  
  - supports resilience planning  
  **Drawbacks:**  
  - requires specialised environments  
  - may not reflect typical use.

- **Closed box testing**  
  Testing without knowledge of internal structure.  
  **Purpose:** to assess functionality based on inputs and outputs only.  
  **Benefits:**  
  - tester independence  
  - focuses on user-facing behaviour  
  **Drawbacks:**  
  - limited coverage of internal logic  
  - may miss hidden defects.

- **Open box testing**  
  Testing with full knowledge of internal structure.  
  **Purpose:** to verify internal logic, paths and conditions.  
  **Benefits:**  
  - thorough coverage of code  
  - identifies internal defects  
  **Drawbacks:**  
  - requires technical expertise  
  - less representative of user behaviour.

## Exam Focus
You should be able to:
- Define testing methods
- Explain the purpose of each testing method
- Compare benefits and drawbacks of different testing methods
- Identify when each testing method is used
- Make justified judgements about testing method suitability

!!! tip "Exam tip"
    Questions may require comparison or justification of testing methods. Responses should weigh benefits and drawbacks and justify suitability based on stage of development, risk and intended outcomes.
