# 1.3.4 Event Tree Analysis (ETA)

---

## What Is Event Tree Analysis?
**Event Tree Analysis (ETA)** is a **root cause and risk analysis technique** used to explore the **possible outcomes** of an initiating event by following different paths based on subsequent decisions or system responses.

ETA is **forward-looking**, focusing on *what could happen next*.

---

## Purpose of Event Tree Analysis
ETA is used to:
- Understand how an initial event can lead to multiple outcomes
- Identify possible success and failure paths
- Assess risk and consequences
- Support contingency and safety planning

ETA is commonly used in **risk assessment** and **safety-critical systems**.

---

## Key Concepts

### Initiating Event
- The starting point of the analysis  
  *(e.g. system failure, user error, security breach)*

### Branches
- Decision points or system responses
- Each branch represents **success or failure**

### Outcomes
- The final result at the end of each path
- May be safe, degraded, or catastrophic

---

## How Event Tree Analysis Works

1. Identify the **initiating event**
2. Determine the first system response or decision
3. Branch into **success/failure outcomes**
4. Repeat for subsequent events
5. Identify all possible final outcomes
6. Assess risk and likelihood of each path

---

## Example
**Initiating event:** Server overload

- Load balancer activates?  
  - Yes → System continues normally  
  - No → Server crashes  

- Backup server available?  
  - Yes → Service restored  
  - No → Prolonged outage  

Each path leads to a different **outcome** with different risks.

---

## Strengths of Event Tree Analysis
- Clearly shows cause-and-effect relationships
- Supports visual understanding of risk paths
- Useful for contingency and disaster planning
- Identifies multiple possible outcomes

---

## Limitations of Event Tree Analysis
- Can become complex very quickly
- Requires accurate system knowledge
- Not suitable for identifying root causes
- Less effective for simple problems

---

## When Event Tree Analysis Is Suitable
ETA is most appropriate when:
- Analysing **consequences** of an event
- Planning responses to failures
- Working with safety-critical or high-risk systems
- Evaluating system resilience

---

## When Event Tree Analysis Is Not Suitable
ETA may be unsuitable when:
- The root cause needs to be identified
- The problem is simple
- Time is limited

In these cases, techniques such as the **Five Whys** or **FMEA** may be more appropriate.

---

## Evaluation Summary

| Strengths | Limitations |
|---------|------------|
| Shows multiple outcomes | Can be complex |
| Good for risk analysis | Not root-cause focused |
| Supports planning | Requires detailed system knowledge |

---

## Exam Focus
You should be able to:
- **Explain** what Event Tree Analysis is
- **Describe** how it is carried out
- **Evaluate** its suitability in a scenario
- Compare ETA with other analysis techniques

!!! tip "Exam tip"
If a question focuses on **possible outcomes after an event**, ETA is usually the most appropriate technique.
