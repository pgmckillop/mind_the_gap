 2.11.1  

 
![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.11  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.11.1 Know and understand the algorithms for searching, how they work and when they are used

This section covers linear search and binary search algorithms, how each operates, and when they are applied in digital software development.

## Linear search

### Features / Characteristics / Role

Linear search checks each item in a data set one at a time, starting from the beginning and continuing until the target value is found or all items have been examined.

### Benefits

- simple to implement  
- works with unsorted data  
- requires no preparation of the data set  
- suitable for small data collections  

### Drawbacks

- slow for large data sets  
- requires checking every item in the worst case  
- inefficient compared to other search methods  

---

## Binary search

### Features / Characteristics / Role

Binary search repeatedly divides a sorted data set in half to locate a target value. At each step, the middle item is compared and half of the remaining items are discarded.

### Benefits

- significantly faster than linear search on large data sets  
- reduces number of comparisons required  
- efficient for repeated searches on sorted data  

### Drawbacks

- requires data to be sorted  
- additional processing may be needed to maintain order  
- more complex to implement than linear search  

---

## When searching algorithms are used

### Features / Characteristics / Role

Searching algorithms are used to locate specific values within collections of data, particularly where rapid retrieval is required or repeated searches are performed.

### Benefits

- enables efficient access to stored data  
- supports data-driven decision making  

### Drawbacks

- inappropriate choice of algorithm reduces performance  

---

## Judgement

Suitability depends on:

i. size of the data set  
ii. whether data is already sorted  
iii. frequency of searches  
iv. performance requirements  
v. developer experience  

Linear search is suitable for small or unsorted data sets, while binary search is suitable for large, sorted collections where faster retrieval is required.

---

!!! tip "Exam tip"
    Marks are awarded for explaining how each algorithm works and when it is used. Avoid stating that one is “faster” — link data size and sorting to suitability.
