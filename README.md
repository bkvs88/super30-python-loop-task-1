# super30-python-loop-task-1
Python for Loop Fundamentals

# Python Basic Programming Challenges

A collection of foundational Python scripts designed to practice loops, conditional statements, lists, dictionaries, and string manipulation.

## 🚀 Challenge Overview

This repository contains solutions to the following 12 Python programming exercises:

### 1. Basic Loops & Arithmetic
* **Numbers 1 to 100:** Prints numbers from 1 to 100 using both `for` loops (with `range()`) and `while` loops.
* **Even Numbers:** Filters and prints all even numbers between 1 and 100 using sequential step-ranges and modulo filtering.
* **Odd Numbers:** Filters and prints all odd numbers between 1 and 100 using sequential step-ranges and modulo filtering.
* **Multiplication Table:** Takes an integer input `n` from the user and prints its multiplication table from 1 up to 20.
* **Sum of Numbers:** Calculates the cumulative sum of numbers from 1 to `n` using a loop.
* **Factorial Calculator:** Accepts a user-input number and calculates its factorial iteratively using a `while` loop without built-in math functions.

### 2. Working with Collections (Lists & Dictionaries)
* **Divisible by 3:** Iterates through the list `numbers = [12, 7, 9, 20, 33, 42, 8, 15]` and appends items divisible by 3 into a new list.
* **String Lengths in a List:** Iterates through `languages = ["Python", "Java", "C++", "JavaScript", "Go"]` and prints each language along with its calculated length.
* **Dictionary Iteration:** Uses the `.items()` method to unpack and print every key-value pair from a `student` profile dictionary.

### 3. String & Algorithm Logic
* **Vowel Counter:** Counts how many total vowels exist in a user-provided string.
* **String Reversal:** Reverses a string (such as `"HELLO"`) using a pure element-wise iteration loop without slicing modifiers or built-in helper tools.
* **Find Maximum:** Scans a list of numbers to extract the largest value manually using logical conditional checks instead of `max()`.

---

## 📂 Repository Structure

The solutions are mapped across the files as follows:

| Challenge Description | Associated Implementation File |
| :--- | :--- |
| Print numbers 1 to 100 | `print_1_to_100.ipynb` |
| Print all even numbers from 1 to 100 | `even_numbers.ipynb` |
| Print all odd numbers from 1 to 100 | `odd_numbers.ipynb` |
| Multiplication table from 1 to 20 | `multiplication_table.ipynb` |
| Calculate the sum of numbers from 1 to n | `sum_of_numbers.ipynb` |
| Factorial without built-in functions | `factorial_calculator.ipynb` |
| Print numbers divisible by 3 | `divisible_by_three.ipynb` |
| Print languages along with their length | `language_lengths.ipynb` |
| Iterate through a student dictionary | `student_dict_iteration.ipynb` |
| Count vowels in a string | `vowel_counter.ipynb` |
| Reverse a string using a loop | `string_reversal.ipynb` |
| Find the largest number from a list | `find_largest_number.ipynb` |

---

## 🛠️ How to Run the Notebooks

### Prerequisites
Ensure you have Jupyter Notebook or JupyterLab installed alongside Python 3.13+:
```bash
pip install jupyter
```

### Execution
Clone the repository and launch the Jupyter interface to interact with your solutions:
```bash
# Clone this repository
git clone https://github.com

# Navigate into the project folder
cd YOUR_REPOSITORY_NAME

# Start the Jupyter Notebook server
jupyter notebook
```

---

## 📝 Technologies Used
* **Language:** Python 3.13
* **Environment:** Jupyter Notebooks (`.ipynb`)
* **Core Concepts:** `for` loops, `while` loops, conditional branching (`if-else`), sequence structures, dictionary expansion, and manual accumulator algorithms.
