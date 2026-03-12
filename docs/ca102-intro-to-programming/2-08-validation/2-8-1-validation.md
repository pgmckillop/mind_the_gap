# 2.8.1

![Retained](../../assets/icons/retained.svg){ width="256" }  
This content was covered in the old specification as topic(s) in 2.8
If you have access to the textbooks, you can use those resources to enhance your understanding.

# 2.8.1 Know the definition of validation and understand the purpose and when validation checks are used

This section covers what validation is, its role in ensuring data quality, and when different validation checks are applied in digital software development.

## Definition of validation

### Features / Characteristics / Role

Validation is the process of checking that data entered into a system meets defined rules and constraints before it is processed or stored. It is used to prevent incorrect, incomplete or inappropriate data from entering a solution.

### Benefits

- improves accuracy of stored data
- reduces processing errors
- supports reliable system behaviour
- protects against invalid input
- improves overall data quality

### Drawbacks

- requires additional development effort
- does not guarantee data is correct, only that it meets rules
- poorly designed validation can restrict legitimate input

---

## Presence check

### Features / Characteristics / Role

A presence check confirms that required data has been entered and that fields are not left empty.

### Benefits

- prevents missing essential information
- supports completeness of records

### Drawbacks

- does not verify correctness of entered data

---

## Length check

### Features / Characteristics / Role

A length check ensures that input data contains the required number of characters or falls within a specified limit.

### Benefits

- prevents overly short or long entries
- supports consistent data storage

### Drawbacks

- does not confirm validity of content

---

## Range check

### Features / Characteristics / Role

A range check verifies that numeric or date values fall within defined minimum and maximum limits.

### Benefits

- prevents unrealistic or out-of-bound values
- supports logical consistency

### Drawbacks

- valid values outside the range may be rejected

---

## Type check

### Features / Characteristics / Role

A type check ensures that data entered matches the expected data type.

### Benefits

- prevents incompatible data from being processed
- supports accurate calculations and comparisons

### Drawbacks

- requires correct definition of expected types

---

## Format check

### Features / Characteristics / Role

A format check confirms that data follows a required pattern or structure.

### Benefits

- supports standardised data entry
- improves compatibility with other systems

### Drawbacks

- correctly formatted data may still be incorrect

---

## Check digit

### Features / Characteristics / Role

A check digit uses a calculated value to confirm that a number has been entered correctly.

### Benefits

- detects common data entry errors
- improves integrity of reference numbers

### Drawbacks

- increases processing complexity
- does not confirm that data is meaningful

---

### Sample question on Check Digits

Describe the **four** steps in the process of using a check digit to validate an input.

### Response

- Remove the leftmost/rightmost digit from the inputted data [1]
- Apply an algorithm to calculate the expected check digit [1]
- Compare the expected value to the check digit [1]
- Accept the data if both are equal [1]

---

## When validation checks are used

### Features / Characteristics / Role

Validation checks are applied whenever data is entered into a system to reduce errors before storage or processing.

### Benefits

- improves reliability of input data
- reduces downstream correction effort

### Drawbacks

- cannot detect all types of errors

---

## Judgement

Suitability depends on:

i. criticality of data accuracy  
ii. volume of input data  
iii. complexity of validation rules  
iv. user experience requirements  
v. system performance constraints

Validation checks are suitable for improving data quality at the point of entry, but must be balanced against usability and performance considerations.

---

!!! tip "Exam tip"
Marks are awarded for linking validation methods to data quality. Avoid listing checks — explain how each prevents specific input errors and affects suitability.
