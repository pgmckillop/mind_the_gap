# 2.2.3 Data Type Conversion Functions

---

## Definition and Purpose
**Data type conversion functions** are used to change a value from one data type to another.  
They are required when:
- data is received in an unexpected format
- operations require compatible data types
- values must be represented differently for processing or output

Type conversion helps ensure programs run correctly and avoid runtime errors.

---

## Conversions in Scope (Appendix 2)

The following conversion functions are defined within the specification and Appendix 2.

---

### `int()`
Converts a value to an **integer**.

**Used when:**
- whole number calculations are required
- numeric input is received as text
- decimals must be removed (by truncation)

**Notes:**
- decimal values are truncated, not rounded
- invalid conversions cause errors

---

### `float()`
Converts a value to a **floating-point number**.

**Used when:**
- calculations require decimal precision
- numeric input must support fractional values

**Notes:**
- integers are converted to equivalent decimal form
- non-numeric values cause errors

---

### `str()`
Converts a value to a **string**.

**Used when:**
- displaying values to users
- combining text and numeric data
- writing data to text-based outputs

**Notes:**
- numeric and Boolean values can be converted safely
- converted values are treated as text

---

### `bool()`
Converts a value to a **Boolean**.

**Used when:**
- evaluating conditions
- controlling program flow
- checking the presence or absence of values

**Notes:**
- empty values convert to `False`
- non-empty or non-zero values convert to `True`

---

## Why Type Conversion Is Necessary
Type conversion is required to:
- ensure compatible operations
- prevent type mismatch errors
- correctly interpret user input
- control logic and decision-making

Failure to convert data correctly can result in:
- program crashes
- incorrect outputs
- logical errors

---

## Exam Focus
You should be able to:
- Define data type conversion
- Identify when type conversion is required
- Select the correct conversion function for a given situation

!!! tip "Exam tip"
Answers should clearly **link the conversion function to the problem being solved**, not just name the function.
