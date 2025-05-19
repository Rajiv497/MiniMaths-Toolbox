# 🧠 LogicLab JS

A collection of JavaScript-based mini logic tools and utilities that demonstrate basic programming skills and problem-solving techniques using HTML, CSS, and JavaScript.

---

## 🚀 Features

This project includes the following modules:

### ✅ 1. Calculator Tool
- Performs Addition, Subtraction, Multiplication, and Division.
- Inputs: Two numbers (`a`, `b`) and the operation type (`+`, `-`, `*`, `/`).
- Built using a JavaScript class.

### ✅ 2. Odd Number Series Generator (Problem 2)
- Generates the first `n` odd numbers.
- Example: input `a = 4` → Output: `1, 3, 5, 7`.

### ✅ 3. Conditional Odd Series Generator (Problem 3)
- Returns the first `n` odd numbers **only if `n` is odd**, otherwise returns the series up to the last odd number less than or equal to `n`.
- Example: `a = 5` → Output: `1, 3, 5, 7, 9`, `a = 4` → Output: `1, 3, 5`.

### ✅ 4. Multiples Counter (Problem 4)
- From an array, counts how many numbers are divisible by 1–9.
- Input: `[1, 2, 8, 9, 12, 46, 76, 82, 15, 20, 30]`
- Output:
  ```json
  {
    "1": 11, "2": 8, "3": 4, "4": 4, "5": 3,
    "6": 2, "7": 0, "8": 1, "9": 1
  }
logiclab-js/
├── calculator.html
├── problem2.html
├── problem3.html
├── problem4.html
├── style.css
├── README.md
git clone https://github.com/yourusername/logiclab-js.git
cd logiclab-js
