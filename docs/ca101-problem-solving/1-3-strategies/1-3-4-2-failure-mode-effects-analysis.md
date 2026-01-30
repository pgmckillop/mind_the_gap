# 1.3.4 Failure Modes and Effects Analysis (FMEA)

---

## What Is FMEA?
**Failure Modes and Effects Analysis (FMEA)** is a **structured root cause analysis technique** used to identify:
- how a system or process might fail (**failure modes**)
- the **effects** of those failures
- actions to **reduce risk** before failures occur

FMEA is **preventative**, not reactive.

---

## Purpose of FMEA
FMEA is used to:
- Identify potential failures **before** they happen
- Reduce risk in systems and processes
- Improve reliability, safety, and quality
- Prioritise issues based on impact

It is commonly used in **complex, technical, or safety-critical systems**.

---

## Key Concepts

### Failure Mode
- A specific way in which something could fail  
  *(e.g. incorrect data input, hardware failure, logic error)*

### Effect
- What happens if the failure occurs  
  *(e.g. system crash, incorrect output, data loss)*

### Cause
- Why the failure might occur  
  *(e.g. poor design, lack of validation, user error)*

---

## How FMEA Works (Simplified Process)

1. **Identify the system or process**
2. List possible **failure modes**
3. Identify the **effects** of each failure
4. Identify the **causes** of each failure
5. Evaluate risk (severity and likelihood)
6. Decide on **mitigation actions**
7. Review and update the analysis

---

## Risk Evaluation in FMEA
FMEA often considers:
- **Severity** – how serious the effect is
- **Likelihood** – how often the failure might occur
- **Detectability** – how easy it is to detect the failure

Failures with **high impact and high likelihood** are prioritised.

---

## Example
**System:** Online booking system  

| Failure Mode | Cause | Effect |
|-------------|------|--------|
| Payment fails | Server timeout | Booking not completed |
| Incorrect date saved | Input validation missing | Incorrect reservations |
| Duplicate bookings | Concurrency issue | Overbooking |

Actions might include:
- Improved validation
- Load testing
- Transaction locking

---

## Strengths of FMEA
- Proactive approach to problem solving
- Reduces risk before deployment
- Structured and systematic
- Well suited to complex systems

---

## Limitations of FMEA
- Time-consuming to carry out
- Requires good system knowledge
- Can become complex and resource-intensive
- Less effective for simple problems

---

## When FMEA Is Suitable
FMEA is most appropriate when:
- Systems are complex or technical
- Failure could have serious consequences
- Risk reduction is critical
- Planning or design is taking place

---

## When FMEA Is Not Suitable
FMEA may be unnecessary when:
- Problems are simple
- Quick diagnosis is required
- Root cause is already known

In these cases, techniques such as the **Five Whys** may be more appropriate.

---

## Evaluation Summary

| Strengths | Limitations |
|---------|------------|
| Prevents failures | Time-consuming |
| Reduces risk | Requires expertise |
| Structured approach | Overkill for simple issues |

---

## Exam Focus
You should be able to:
- **Explain** what FMEA is
- **Describe** how FMEA is carried out
- **Evaluate** its suitability in a scenario
- Compare FMEA with other root cause analysis techniques

!!! tip "Exam tip"
Evaluation answers should link **risk, complexity, and consequences** to why FMEA is (or is not) appropriate.
