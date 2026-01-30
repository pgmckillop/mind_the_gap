# 2.9.7 Suitability — Paired Examples and Judgements
E
The examples below show how **two valid solutions** can exist, but one may be **more suitable** than the other depending on context.

---

## Example 1 — Counting User Attempts

### Scenario
A program must allow a user **three login attempts** before locking access.

---

### Solution A

```python
attempts = 0
while attempts < 3:
    password = input("Enter password: ")
    attempts += 1


## Judgement

Both solutions work correctly. However, **Solution B is more suitable** because the number of repetitions is known in advance. A `for` loop is clearer, easier to read, and less error-prone than a `while` loop in this context.

A `while` loop would be more suitable if the number of attempts was unknown.

---

## Example 2 — Menu Selection

### Scenario
A program allows users to select from **six fixed menu options**.

### Example a

```python
if choice == 1:
    print("Add")
elif choice == 2:
    print("Edit")
elif choice == 3:
    print("Delete")


### Example B

```python
match choice:
    case 1:
        print("Add")
    case 2:
        print("Edit")
    case 3:
        print("Delete")


## Example 3 — Repeated Calculation
Scenario

A program calculates VAT in several different places.

Solution A

```python
price = price * 1.2


(repeated multiple times)

Solution B

```python
def calculate_vat(price):
    return price * 1.2

## Judgement

Solution B is more suitable because it reduces code duplication and improves maintainability. If the VAT rate changes, only one part of the program needs to be updated.


## Example 4 — Input Validation
Scenario

A program asks the user to enter their age.

Solution A

```python
age = int(input("Enter age: "))

Solution B

```python
try:
    age = int(input("Enter age: "))
except ValueError:
    print("Invalid input")

## Judgement

While both solutions accept input, Solution B is more suitable because it handles invalid input safely. This makes the program more robust and user-friendly.


## Example 5 — Data Storage Choice
Scenario

A program stores student names and grades.

Solution A

```python
names = ["Alex", "Sam"]
grades = [80, 65]

Solution B

```python
students = {"Alex": 80, "Sam": 65}

## Judgement

Solution B is more suitable because it groups related data together and makes access clearer. Using a dictionary reduces the risk of mismatched data and improves readability.