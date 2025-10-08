# Math Utility Scripts 🧮

This repository contains two simple Python programs that perform basic mathematical computations.  
They are designed to demonstrate user input handling, function creation, and the use of Python’s built-in math library.

---

## 📁 Files

### 1. `task 1.py`
**Description:**  
Calculates the factorial of a given number using a loop.

**Code Overview:**
```python
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact
```

**Usage:**
```bash
python task\ 1.py
```
**Example Output:**
```
Enter a number: 5
Factorial of 5 is: 120
```

---

### 2. `task 2.py`
**Description:**  
Performs three mathematical operations on a user-provided number:
- Square root  
- Natural logarithm  
- Sine

**Code Overview:**
```python
import math

num = float(input("Enter a number: "))
square_root = math.sqrt(num)
logarithm = math.log(num)
sine = math.sin(num)
```

**Usage:**
```bash
python task\ 2.py
```
**Example Output:**
```
Enter a number: 9
Square root: 3.0
Logarithm: 2.1972245773362196
Sine: 0.4121184852417566
```

---

## 🧠 Requirements

- Python 3.6 or higher  
- No additional libraries required (uses only Python’s standard library)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/math-utility-scripts.git
   ```
2. Navigate into the project folder:
   ```bash
   cd math-utility-scripts
   ```
3. Run any of the scripts:
   ```bash
   python task\ 1.py
   # or
   python task\ 2.py
   ```

