# 2.11.2  


![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.11  
If you have access to the textbooks, you can use those resources to enhance your understanding.  

# 2.11.2 Know and understand the algorithms for sorting, how they work and when they are used

This section covers bubble sort, insertion sort and merge sort algorithms, how each operates, and when they are applied in digital software development.

## Bubble sort

### Features / Characteristics / Role

Bubble sort repeatedly compares adjacent items and swaps them if they are in the wrong order. This process continues through multiple passes until no further swaps are required.

### Benefits

- simple to understand and implement  
- works on unsorted data  
- requires no additional data structures  

### Drawbacks

- inefficient for large data sets  
- requires many comparisons and swaps  
- slow execution time compared to other methods  

---

## Insertion sort

### Features / Characteristics / Role

Insertion sort builds a sorted list one item at a time by taking each new element and inserting it into its correct position within the already sorted portion.

### Benefits

- efficient for small data sets  
- performs well on nearly sorted data  
- simple implementation  

### Drawbacks

- slow for large data sets  
- requires shifting of elements  
- performance decreases as data size increases  

---

## Merge sort

### Features / Characteristics / Role

Merge sort divides a data set into smaller parts, sorts each part, and then merges them back together in order.

### Benefits

- efficient for large data sets  
- consistent performance  
- suitable for sorting large collections  

### Drawbacks

- requires additional memory  
- more complex to implement  
- overhead may outweigh benefits for small data sets  

---

## When sorting algorithms are used

### Features / Characteristics / Role

Sorting algorithms are used to arrange data into a defined order, enabling faster searching, clearer presentation and structured processing.

### Benefits

- supports efficient searching  
- improves organisation of data  
- enables predictable processing  

### Drawbacks

- sorting introduces processing overhead  

---

## Judgement

Suitability depends on:

i. size of the data set  
ii. level of existing order  
iii. available memory resources  
iv. performance requirements  
v. developer experience  

Bubble and insertion sort are suitable for small or simple data sets, while merge sort is suitable for large collections where consistent performance is required.

---

!!! tip "Exam tip"
Marks are awarded for explaining how each sorting algorithm works and when it is used. Avoid listing algorithms — link data size and performance to suitability.
