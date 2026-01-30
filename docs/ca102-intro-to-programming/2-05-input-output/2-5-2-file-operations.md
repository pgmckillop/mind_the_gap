# 2.5.2 Text Files for Input and Output

---

## Purpose of Using Text Files
Text files can be used to:
- **store data persistently** (so it remains available after the program ends)
- **read stored data** as input for processing
- **output results** in a simple, portable format

---

## Opening a File for Reading
A text file must be opened in **reading** mode to allow the program to take input from it.

**Key points:**
- the program accesses existing file contents
- the file must be opened before data can be read

---

## Opening a File for Writing
A text file must be opened in **writing** mode to allow the program to output data to it.

**Key points:**
- the program writes new data to the file
- the file must be opened before writing can occur

---

## Writing Lines to the File
When a file is opened for writing, the program can **write lines** of text into it.

**Key points:**
- output is written in a textual format
- data is recorded as lines in the file

---

## Closing the File
Files should be **closed** after reading or writing.

**Why this matters:**
- ensures data is saved correctly (after writing)
- releases the file resource so it can be used elsewhere
- reduces the risk of file corruption or access issues

---

## Exam Focus
You should be able to:
- Explain how text files are used for input and output
- Describe the steps: open for reading, open for writing, write lines, close
- Identify what each step enables a program to do

!!! tip "Exam tip"
Answers that follow the **correct sequence of file operations** tend to gain marks more reliably.


## Opening a File for Reading
A file must be opened in **read mode** before data can be accessed.

```python
file = open("input.txt", "r")

```python
# Open a file for writing
file = open("output.txt", "w")
file.write("Hello World\n")
file.close()

# Open the file for reading
file = open("output.txt", "r")
content = file.read()
file.close()

