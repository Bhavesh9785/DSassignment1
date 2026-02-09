This repository contains a collection of Python programs demonstrating core programming concepts such as command-line arguments, comparison operators, exception handling, list comprehensions, and user-defined functions.

---

## 📌 Contents

### 1. Prime Number Checker (Command-Line Arguments)

**Description:**  
This program checks whether a given number is a prime number using command-line arguments.

**Concepts Used:**
- `sys.argv`
- Command-line input
- Functions
- Conditional statements
- Exception handling

**How to Run:**
```bash
python prime_check.py 42
````

**Example Output:**

```
42 is not a prime number.
```

---

### 2. Difference Between `is` and `==` Operators

**Description:**
This program demonstrates the difference between:

* `==` (value equality)
* `is` (object identity)

The comparison is shown using integers and lists.

**Concepts Used:**

* Data types (int, list)
* Comparison operators
* Object identity

**Key Takeaways:**

* `==` compares values
* `is` checks whether two variables refer to the same object in memory

---

### 3. List Processing with Exception Handling

**Description:**
This program iterates through a list and:

* Skips negative numbers
* Stops execution when zero is encountered
* Handles non-integer values using exception handling

**Concepts Used:**

* Loops
* Conditional statements
* `try` / `except`
* `continue` and `break`
* Type conversion

**Sample Output:**

```
Processing positive number: 1
Skipping negative number: -8
Processing positive number: 2
Encountered zero. Stopping execution.
```

---

### 4. Squares Using List Comprehension

**Description:**
Generates a list of squares of numbers from 1 to 20 that are divisible by both 2 and 5 using a single list comprehension.

**Concepts Used:**

* List comprehension
* `range()`
* Modulus operator
* Conditional filtering

**Output:**

```
[100, 400]
```

---

### 5. Find Smallest and Largest Values in a List

**Description:**
A user-defined function that returns the smallest and largest numbers from a list without using built-in functions like `min()` or `max()`.

**Concepts Used:**

* User-defined functions
* List traversal
* Conditional logic
* Multiple return values

**Example Output:**

```
Smallest: 2, Largest: 53
```

---

## 🛠 Technologies Used

* Python 3
* Standard Python libraries

---

## 📂 How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/repository-name.git
```

2. Navigate to the project directory:

```bash
cd repository-name
```

3. Run any Python file using:

```bash
python filename.py
```

---
