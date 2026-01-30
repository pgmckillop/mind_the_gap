# 2.12.4 Test Data and Test Plan

---

## Purpose of Test Data and Test Plans
**Test data** and **test plans** are used to ensure a solution is tested systematically and thoroughly.  
They support:
- verification of correct behaviour
- identification of defects
- evidence that requirements have been met

---

## 2.12.4.1 Types of Test Data

### Valid Test Data
**Definition:**  
Data that meets all validation rules.

**Purpose:**  
- confirm the system accepts correct input
- verify normal operation

**Used when:**  
- checking expected behaviour under normal conditions

---

### Invalid Test Data
**Definition:**  
Data that breaks one or more validation rules.

**Purpose:**  
- confirm the system rejects incorrect input
- verify error handling

**Used when:**  
- testing input validation

---

### Boundary Test Data
**Definition:**  
Data at the limits of acceptable values.

**Purpose:**  
- identify errors at input boundaries

**Used when:**  
- values have defined minimums or maximums

---

### Erroneous Test Data
**Definition:**  
Data that is of the wrong type or format.

**Purpose:**  
- test robustness against unexpected input
- verify defensive handling

**Used when:**  
- testing system resilience

---

## 2.12.4.2 Creating Test Data

Creating test data involves:
- identifying validation rules
- selecting representative values
- ensuring all input conditions are covered

Effective test data:
- covers normal, abnormal, and extreme cases
- aligns directly with system requirements
- supports repeatable testing

---

## 2.12.4.3 Test Plan: Steps and Structure

### Purpose of a Test Plan
A **test plan** defines how testing will be carried out.  
It ensures testing is:
- structured
- traceable
- repeatable

---

### Steps and Structure of a Test Plan

A test plan includes:

- **identifying tests to be carried out**  
  defines what will be tested

- **describing the purpose of each test**  
  explains why the test is required

- **identifying test data to be used**  
  specifies valid, invalid, boundary, or erroneous data

- **describing expected results**  
  defines correct system behaviour

- **recording actual results**  
  captures what happened during testing

---

## When Test Plans Are Used
Test plans are used:
- before and during testing
- to guide testers
- to provide evidence of testing activity

They support accountability and quality assurance.

---

## Exam Focus
You should be able to:
- define valid, invalid, boundary, and erroneous test data
- explain how test data is created
- describe the steps and structure of a test plan
- explain when test plans are used

!!! tip "Exam tip"
Marks are often awarded for **linking test data types to validation and explaining how test plans ensure structured testing**, not just listing components.
