## 2.11 Common algorithms

## Algorithm processing

### How common algorithms process their tasks

**Linear search** processes its task by checking each item in a data set one at a time, starting from the beginning and continuing sequentially until the required item is found or all items have been checked.

**Binary search** processes its task by repeatedly dividing a sorted data set into halves, comparing the target value with the middle item, and eliminating half of the remaining items on each comparison.

**Bubble sort** processes its task by repeatedly stepping through the data set, comparing adjacent items and swapping them if they are in the wrong order, continuing until no further swaps are required.

**Insertion sort** processes its task by taking one item at a time and inserting it into its correct position within an already sorted portion of the data set, gradually building a sorted list.

**Merge sort** processes its task by dividing the data set into smaller sub-sets, sorting those sub-sets, and then merging them back together in the correct order to produce a fully sorted data set.


### 2.11.5 Best case, worst case and average case
Best case, worst case and average case are measures used to describe the performance of algorithms under different conditions, using logical reasoning rather than formal notation.

- **Best case**  
  Describes the most efficient scenario in which an algorithm completes its task using the least amount of processing.  
  **Purpose:** to identify the most favourable conditions for algorithm performance.  
  **Benefits:**  
  - demonstrates potential maximum efficiency  
  - useful for understanding optimal conditions  
  **Drawbacks:**  
  - may not reflect typical or realistic use  
  - limited value when used in isolation.

- **Worst case**  
  Describes the least efficient scenario in which an algorithm requires the greatest amount of processing to complete its task.  
  **Purpose:** to identify performance limits and potential inefficiencies.  
  **Benefits:**  
  - supports evaluation of reliability under heavy demand  
  - useful for risk assessment and planning  
  **Drawbacks:**  
  - may overstate performance cost for typical use  
  - can discourage suitable algorithms if considered alone.

- **Average case**  
  Describes the expected performance of an algorithm across typical or mixed conditions.  
  **Purpose:** to provide a realistic indication of algorithm behaviour in normal use.  
  **Benefits:**  
  - supports balanced judgement of performance  
  - more representative of real-world use  
  **Drawbacks:**  
  - dependent on assumptions about typical data  
  - may be harder to reason about precisely.

## Best Worst Average for Search
| Algorithm       | Best Case                                                                 | Average Case                                                             | Worst Case                                                                |
|-----------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Linear search** | The required item is found at the beginning of the data set, so the search stops immediately. | The required item is found somewhere in the middle of the data set after several comparisons. | The required item is not present or is found at the end of the data set, so every item must be checked. |
| **Binary search** | The required item is found at the first comparison, when the middle value matches the search value. | The required item is found after several divisions of the data set as the search space is repeatedly reduced. | The required item is not present or is found only after the maximum number of divisions, requiring repeated halving of the data set. |


### 2.11.6 Suitability of algorithms for searching
Judgements about the suitability of searching algorithms are based on performance under best, worst and average cases, and the characteristics of the data.

**Benefits of selecting a suitable searching algorithm**
- improves efficiency of data retrieval  
- reduces unnecessary processing  
- supports reliable system performance.

**Drawbacks of unsuitable selection**
- increased execution time  
- inefficient use of resources  
- reduced system responsiveness.

Suitability judgements consider how an algorithm performs across different cases and how well it matches the structure and organisation of the data being searched.

### 2.11.7 Suitability of algorithms for sorting
Judgements about the suitability of sorting algorithms are based on performance, resource use and complexity under different cases.

**Benefits of selecting a suitable sorting algorithm**
- improves efficiency of data organisation  
- supports faster searching and processing  
- reduces unnecessary computation.

**Drawbacks of unsuitable selection**
- increased processing time  
- inefficient use of memory  
- unnecessary complexity in implementation.

Suitability judgements consider how algorithms perform in best, worst and average cases and whether their complexity is appropriate for the size and nature of the data set.

## Best Worst Average for Sort Algorithms

| Algorithm        | Best Case                                                                 | Average Case                                                             | Worst Case                                                                |
|------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------|
| **Bubble sort**    | The data set is already sorted, so only a single pass is required with no swaps. | Elements require multiple passes with repeated comparisons and swaps.    | The data set is in reverse order, requiring repeated passes and the maximum number of swaps. |
| **Insertion sort** | The data set is already sorted, so each element is placed in position with minimal comparisons. | Elements are inserted into their correct position after several comparisons and shifts. | The data set is in reverse order, requiring each element to be compared and shifted through the entire sorted portion. |
| **Merge sort**     | The data set is divided and merged efficiently, with consistent performance regardless of initial order. | Performance remains consistent as the data is always divided and merged in the same way. | Performance remains consistent, as all elements must still be divided and merged regardless of order. |


## Exam Focus
You should be able to:
- Explain best case, worst case and average case performance
- Apply logical reasoning to compare algorithm performance
- Make justified judgements about searching algorithm suitability
- Make justified judgements about sorting algorithm suitability
- Weigh efficiency and performance when selecting algorithms

!!! tip "Exam tip"
    Questions may require judgement rather than description. Responses should compare best, worst and average cases and justify algorithm suitability by linking performance and efficiency to the context of searching or sorting tasks.
