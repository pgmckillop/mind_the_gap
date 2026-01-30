# 2.11.4 Metrics to Compare Algorithms

---

## Purpose of Algorithm Metrics
**Metrics** are used to compare algorithms objectively.  
They help determine how suitable an algorithm is by measuring:
- efficiency
- resource usage
- practicality for a given problem

The specification defines three metrics:
- **use of memory space**
- **execution time**
- **number of comparisons**

---

## Use of Memory Space

### Definition
**Memory space** refers to the amount of memory an algorithm requires while running.

### Why It Matters
- limited memory environments require efficient use of space
- inefficient memory use can reduce system performance

### Example
- an algorithm that stores large temporary lists uses more memory
- an algorithm that processes data one item at a time uses less memory

### Tools That Can Be Used
- observing variable and data structure usage
- monitoring memory use during execution
- built-in development environment memory indicators

---

## Execution Time

### Definition
**Execution time** is how long an algorithm takes to complete.

### Why It Matters
- slower algorithms may be unsuitable for large data sets
- faster execution improves user experience and system responsiveness

### Example
- searching an unsorted list item by item takes longer as the list grows
- searching a sorted list by repeatedly halving the search space is faster

### Tools That Can Be Used
- timing execution using system clocks
- built-in timing or profiling tools in development environments
- comparing run times using test data of different sizes

---

## Number of Comparisons

### Definition
**Number of comparisons** is the count of times values are compared during execution.

### Why It Matters
- comparisons directly affect execution time
- algorithms with fewer comparisons are often more efficient

### Example
- a simple sorting algorithm may compare every item with every other item
- a more efficient sorting algorithm reduces unnecessary comparisons

### Tools That Can Be Used
- tracing algorithm steps manually
- counting comparison operations during execution
- using debugging tools to follow algorithm flow

---

## Using Metrics Together
Algorithms are rarely judged on a single metric.  
Selection depends on:
- size of the data set
- performance requirements
- available memory

An algorithm that is fast may use more memory, while a memory-efficient algorithm may run more slowly.

---

## Exam Focus
You should be able to:
- define memory space, execution time, and number of comparisons
- explain why each metric is used
- apply metrics to compare algorithms in given scenarios

!!! tip "Exam tip"
Marks are often awarded for **linking the chosen metric to the problem context**, not just describing the metric.
