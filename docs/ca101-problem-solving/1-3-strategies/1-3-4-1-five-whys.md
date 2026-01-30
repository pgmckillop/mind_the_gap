# 1.3.4 Five Whys Technique

---

## What Is the Five Whys?
The **Five Whys** is a **root cause analysis technique** used to identify the underlying cause of a problem by repeatedly asking **“Why?”**.

The process continues until the root cause is identified — this often takes around five questions, but not always exactly five.

---

## Purpose of the Five Whys
The Five Whys is used to:
- Move beyond symptoms and identify the **root cause**
- Prevent the same problem from happening again
- Support effective and long-term solutions
- Improve system reliability and decision-making

---

## How the Five Whys Works
1. **State the problem clearly**
2. Ask **“Why did this happen?”**
3. Use the answer to ask **“Why?”** again
4. Repeat until the underlying cause is identified
5. Implement a solution that addresses the root cause

---

## Example
**Problem:** A website crashed during peak usage.

1. Why did the website crash?  
   → The server stopped responding.

2. Why did the server stop responding?  
   → It ran out of memory.

3. Why did it run out of memory?  
   → Too many requests were being processed.

4. Why were too many requests processed?  
   → There was no request limiting in place.

5. Why was there no request limiting?  
   → It was not considered during system design.

**Root cause:** Missing design consideration for request limiting.

---

## Strengths of the Five Whys
- Simple and quick to apply
- Requires no specialist tools
- Encourages logical thinking
- Effective for **simple or well-understood problems**

---

## Limitations of the Five Whys
- Relies heavily on the knowledge and honesty of participants
- Can oversimplify complex systems
- May stop too early and miss contributing factors
- Less effective for multi-cause or technical failures

---

## When the Five Whys Is Suitable
The Five Whys is most appropriate when:
- The problem is relatively simple
- There is a clear cause-and-effect relationship
- Quick analysis is needed
- The system is well understood

---

## When the Five Whys Is Not Suitable
It may be unsuitable when:
- Multiple root causes exist
- The system is complex or safety-critical
- Quantitative risk analysis is required

In these cases, techniques such as **FMEA** or **Event Tree Analysis** may be more appropriate.

---

## Evaluation Summary

| Strengths | Limitations |
|---------|------------|
| Easy to use | Can oversimplify |
| No tools required | Subjective |
| Encourages deeper thinking | Not suited to complex systems |

---

## Exam Focus
You should be able to:
- **Explain** what the Five Whys is
- **Describe** how the Five Whys is carried out
- **Evaluate** its suitability in a given scenario
- Compare it with other root cause analysis techniques

!!! tip "Exam tip"
Evaluation questions should mention **both**
