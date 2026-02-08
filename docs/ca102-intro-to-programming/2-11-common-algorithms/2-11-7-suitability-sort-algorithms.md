# 2.11.7  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.11  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.11.7 Make judgements about the suitability of using different algorithms for sorting

This section covers how judgements are made when selecting sorting algorithms based on data characteristics and system constraints in digital software development.

## Suitability of sorting algorithms

### Features / Characteristics / Role

Different sorting algorithms provide different performance characteristics depending on data size, existing order and available resources.

Bubble sort repeatedly swaps adjacent values until ordered.  
Insertion sort builds a sorted list one element at a time.  
Merge sort divides data into smaller parts, sorts them, and merges the results.

Selection involves considering execution time, memory usage and complexity of implementation.

### Benefits

- enables informed selection based on problem requirements  
- supports efficient organisation of data  
- improves performance when appropriate algorithms are chosen  
- supports scalability of solutions  

### Drawbacks

- inappropriate selection reduces performance  
- more efficient algorithms may require additional memory  
- simpler algorithms may be too slow for large data sets  
- requires understanding of algorithm behaviour  

---

## Judgement

Suitability depends on:

i. size of the data set  
ii. level of existing order  
iii. available memory resources  
iv. performance requirements  
v. developer experience  

Bubble sort is suitable for very small or simple data sets where ease of implementation is prioritised.  
Insertion sort is suitable for small or nearly sorted data sets where minimal reordering is required.  
Merge sort is suitable for large collections where consistent performance is required, but introduces additional memory overhead.

---

!!! tip "Exam tip"
Marks are awarded for justifying sorting choices. Avoid stating that one algorithm is “better” — link data size, existing order and memory constraints to suitability.


---
---
## Scenario-based selection of sorting algorithms

### Scenario 1: Very small data set

A solution sorts a short list of values where simplicity of implementation is prioritised over performance.

**Suitable approach:** Bubble sort  

**Reasoning:**  
The small data size limits performance impact, making bubble sort acceptable due to its straightforward logic and ease of implementation.

---

### Scenario 2: Nearly sorted data

A solution regularly sorts data that already has most values in the correct order.

**Suitable approach:** Insertion sort  

**Reasoning:**  
Insertion sort performs efficiently when only small adjustments are needed, reducing unnecessary comparisons and shifts.

---

### Scenario 3: Large data set

A solution sorts a large collection of values where consistent performance is required.

**Suitable approach:** Merge sort  

**Reasoning:**  
Dividing the data into smaller parts and merging sorted results provides predictable execution time, making merge sort suitable for large volumes of data.

---

### Scenario 4: Limited memory availability

A system operates under constrained memory conditions and sorts moderate amounts of data.

**Suitable approach:** Bubble sort or insertion sort  

**Reasoning:**  
These algorithms do not require additional memory structures, avoiding the overhead introduced by merge sort.

---

### Scenario 5: Performance-critical processing

A solution repeatedly sorts large data sets where execution speed is a priority.

**Suitable approach:** Merge sort  

**Reasoning:**  
Merge sort provides consistent performance for large collections, justifying its additional memory usage when processing time is critical.

---

## Extended judgement

Suitability depends on:

i. size of the data set  
ii. level of existing order  
iii. available memory resources  
iv. performance constraints  
v. development complexity  

Bubble sort is suitable for very small or simple collections.  
Insertion sort is suitable where data is already partially ordered.  
Merge sort is suitable for large data sets where predictable performance outweighs memory overhead.

---

!!! tip "Exam tip"
Marks are awarded for applying sorting algorithms to context. Avoid naming algorithms alone — link data size, existing order and memory constraints to justify suitability.
