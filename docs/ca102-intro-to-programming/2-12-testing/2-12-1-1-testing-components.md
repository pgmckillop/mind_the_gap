## 2.12 Testing

### 2.12.1.1 Testing components
Testing individual components before integration is used to identify issues early and ensure each part functions correctly in isolation.  
The purpose is to reduce risk when components are combined into the final solution. :contentReference[oaicite:0]{index=0}

- **Software**  
  Testing software components checks that code performs as intended.  
  **Purpose:** to identify defects in logic, processing and behaviour before integration.  
  **Benefits:**  
  - isolates faults to specific code components  
  - simplifies debugging and correction  
  **Drawbacks:**  
  - does not reveal issues caused by interaction with other components  
  - requires additional testing time.

- **Hardware**  
  Testing hardware components checks that physical devices operate correctly.  
  **Purpose:** to ensure reliability and compatibility before system assembly.  
  **Benefits:**  
  - reduces risk of hardware failure in the final solution  
  - identifies faulty or incompatible components early  
  **Drawbacks:**  
  - may require specialised equipment  
  - does not test interaction with software.

- **Data**  
  Testing data checks accuracy, validity and suitability for processing.  
  **Purpose:** to ensure data does not cause errors or incorrect results.  
  **Benefits:**  
  - improves reliability of processing and outputs  
  - reduces risk of data-related faults  
  **Drawbacks:**  
  - may not detect issues caused by data flow between components  
  - requires defined test data sets.

- **Interfaces**  
  Testing interfaces checks the points where components interact.  
  **Purpose:** to ensure correct communication between components.  
  **Benefits:**  
  - identifies communication and compatibility issues  
  - supports smoother integration  
  **Drawbacks:**  
  - limited without full system context  
  - may require repeated testing during integration.

- **Resulting service (final product)**  
  Testing the resulting service evaluates the complete solution after components are combined.  
  **Purpose:** to confirm that all components work together to meet requirements.  
  **Benefits:**  
  - validates overall functionality  
  - identifies issues not visible in isolated testing  
  **Drawbacks:**  
  - faults may be harder to trace to individual components  
  - issues identified late may be costly to resolve.

## Exam Focus
You should be able to:
- Explain why individual components are tested before integration
- Distinguish between testing software, hardware, data and interfaces
- Explain the purpose of testing the resulting service
- Compare benefits and drawbacks of component testing
- Justify testing approaches in relation to risk and fault isolation

!!! tip "Exam tip"
    Questions may require justification of testing components before integration. Responses should focus on fault isolation, risk reduction and the limitations of testing components in isolation versus testing the final solution.
