# 2.11.3  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.11  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.11.3 Know and understand the benefits and drawbacks of using searching and sorting algorithms

This section covers the advantages and limitations of linear search, binary search, bubble sort, insertion sort and merge sort when applied in digital software development.

## Linear search

### Features / Characteristics / Role

Linear search checks each item in sequence until the required value is found or the end of the data set is reached.

### Benefits

- simple to implement  
- works with unsorted data  
- suitable for small data sets  

### Drawbacks

- slow for large collections  
- inefficient compared to other search methods  

---

## Binary search

### Features / Characteristics / Role

Binary search repeatedly halves a sorted data set to locate a target value.

### Benefits

- fast for large sorted data sets  
- significantly reduces number of comparisons  

### Drawbacks

- requires sorted data  
- additional overhead to maintain order  
- more complex to implement  

---

## Bubble sort

### Features / Characteristics / Role

Bubble sort repeatedly compares adjacent values and swaps them until the data set is ordered.

### Benefits

- easy to understand  
- simple implementation  

### Drawbacks

- very slow for large data sets  
- many unnecessary comparisons  

---

## Insertion sort

### Features / Characteristics / Role

Insertion sort builds a sorted list one element at a time by inserting items into their correct position.

### Benefits

- efficient for small or nearly sorted data  
- simple logic  

### Drawbacks

- poor performance on large data sets  
- requires shifting elements  

---

## Merge sort

### Features / Characteristics / Role

Merge sort divides data into smaller parts, sorts them, and merges the results.

### Benefits

- efficient for large data sets  
- consistent performance  

### Drawbacks

- requires additional memory  
- more complex to implement  

---

## Judgement

Suitability depends on:

i. size of the data set  
ii. whether data is already sorted  
iii. available memory resources  
iv. performance requirements  
v. developer experience  

Linear and insertion approaches are suitable for small or simple collections, while binary search and merge sort are suitable for large, structured data where performance is critical.

---

!!! tip "Exam tip"
Marks are awarded for comparing algorithms. Avoid listing benefits and drawbacks — explain how data size, sorting and memory affect suitability.
