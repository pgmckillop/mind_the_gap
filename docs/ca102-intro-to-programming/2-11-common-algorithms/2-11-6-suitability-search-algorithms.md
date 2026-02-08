# 2.11.6  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.11  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.11.6 Make judgements about the suitability of using different algorithms for searching

This section covers how judgements are made when selecting searching algorithms based on problem requirements and system constraints in digital software development.

## Suitability of searching algorithms

### Features / Characteristics / Role

Different searching algorithms provide different performance characteristics depending on data size, structure and preparation. Selection involves considering how data is organised and how frequently searches are performed.

Linear search examines each item sequentially, while binary search repeatedly halves a sorted data set to locate a target value.

### Benefits

- enables informed selection based on data characteristics  
- supports efficient retrieval of information  
- improves overall system performance when appropriate algorithms are chosen  

### Drawbacks

- inappropriate selection reduces performance  
- additional overhead may be required to prepare data  
- requires understanding of algorithm behaviour  

---

## Judgement

Suitability depends on:

i. size of the data set  
ii. whether data is already sorted  
iii. frequency of searches  
iv. performance requirements  
v. developer experience  

Linear search is suitable for small or unsorted data sets or where searches are infrequent. Binary search is suitable for large, sorted collections where rapid retrieval is required, but introduces overhead to maintain ordering.

---

!!! tip "Exam tip"
Marks are awarded for justifying algorithm choice. Avoid stating that one method is “better” — link data size, sorting and performance to suitability.

---
---
## Scenario-based selection of searching algorithms

### Scenario 1: Small, unsorted data set

A solution searches a short list of values that changes frequently and is not stored in sorted order.

**Suitable approach:** Linear search  

**Reasoning:**  
Sorting the data would introduce unnecessary overhead. Sequential checking is sufficient due to the small data size and avoids the cost of maintaining order.

---

### Scenario 2: Large, static data set

A solution repeatedly searches a large collection of values that rarely changes.

**Suitable approach:** Binary search  

**Reasoning:**  
Once sorted, the data can be searched efficiently many times. The reduced number of comparisons significantly improves performance compared to checking every item.

---

### Scenario 3: Frequently updated data

A system performs searches on data that is regularly inserted, removed or modified.

**Suitable approach:** Linear search  

**Reasoning:**  
Maintaining sorted order would introduce continual processing overhead. Sequential searching avoids repeated sorting and supports simpler data management.

---

### Scenario 4: Performance-critical retrieval

A solution requires fast response times when locating values in a large data set.

**Suitable approach:** Binary search  

**Reasoning:**  
Dividing the data set on each comparison reduces execution time, making binary search suitable where performance is a priority and sorted data can be maintained.

---

## Extended judgement

Suitability depends on:

i. size of the data set  
ii. whether data is already sorted or can be kept sorted  
iii. frequency of searches versus updates  
iv. performance constraints  
v. development and maintenance overhead  

Linear search is suitable where data sets are small, frequently changing, or unsorted. Binary search is suitable where data sets are large, stable, and searched repeatedly, provided the cost of sorting is justified by performance gains.

---

!!! tip "Exam tip"
Marks are awarded for applying searching algorithms to context. Avoid naming an algorithm alone — link data size, ordering and frequency of change to justify suitability.

