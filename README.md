# Python Fundamentals Practice Scripts

This repository contains a collection of beginner-friendly Python scripts that demonstrate core programming concepts. The code is divided into easily digestible sections, making it perfect for quick reference or hands-on practice.

##  Overview

The provided Python file contains 13 commented-out blocks of code. Each block focuses on a specific data type, control flow mechanism, or built-in Python function. To test a specific concept, simply uncomment the relevant block and run the script.

##  Concepts Covered

### 1. Control Flow & Logic
* **If/Elif/Else Statements (Block 1):** A basic grade calculator that takes user input to determine a letter grade based on percentage conditions.
* **For Loops & Conditionals (Block 13):** A script that iterates through a string to count the number of vowels and consonants using the `in` operator.

### 2. Dictionaries
* **Creation & Structure (Block 2):** Introduction to key-value pairs.
* **Handling Duplicate Keys (Block 3):** Demonstrates how Python handles duplicate keys (hint: the last assigned value overwrites the previous ones).
* **Dictionary Operations (Block 4):** * Accessing and replacing values using key indexing.
    * Iterating over `keys()`, `values()`, and `items()`.
    * Adding new key-value pairs.
    * Removing pairs using the `pop()` method.

### 3. String Manipulation & Methods
* **Indexing and Slicing (Block 5):** Extracting specific characters and substrings using step slicing (e.g., `[::-1]`, `[1:8:2]`).
* **Searching (Block 6):** Finding substring indexes using the `.find()` method.
* **Joining (Block 7):** Combining iterables of strings into a single string using `.join()`.
* **Case Formatting (Block 8):** Manipulating string cases using `.lower()`, `.upper()`, `.swapcase()`, `.title()`, and `.capitalize()`.
* **String Formatting (Block 9):** Dynamically inserting variables into strings using `.format()`, f-strings, and padding strings with `.zfill()`.
* **Validation Methods (Block 10):** Checking string characteristics returning boolean (`True`/`False`) values using methods like `.isalnum()`, `.isalpha()`, `.isdigit()`, `.isupper()`, `.startswith()`, and more.

### 4. Math & Comparisons
* **Operator Precedence (Block 11):** Demonstrating how parentheses affect the order of arithmetic operations (PEMDAS/BODMAS rule).
* **List Comparison (Block 12):** Using equality (`==`) and inequality (`!=`) operators to compare the contents of different lists.

## 🛠️ How to Use

1. Clone or download the file to your local machine.
2. Ensure you have [Python](https://www.python.org/downloads/) installed.
3. Open the file in your preferred code editor (VS Code, PyCharm, Sublime Text).
4. **Uncomment** the specific block of code you want to test (remove the `#` at the beginning of the lines).
5. Run the script in your terminal:
   ```bash
   python your_file_name.py
