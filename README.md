# Python Fundamentals: Assignment 1

This repository contains a collection of basic Python programs focused on conditional logic, data structures, and input validation. The programs are implemented within a Jupyter Notebook.

## 📁 Contents

The notebook `Python_Assignment_1.ipynb` includes the following programs:

### 1. Grade Calculator
* **Logic:** Inputs a student's marks (0-100) and assigns a grade.
* **Grading Scale:** * 90-100: **A**
    * 80-89: **B**
    * 70-79: **C**
    * Below 70: **Fail**

### 2. User Login Verification
* **Logic:** Verifies login credentials against a predefined dictionary of registered users.
* **Features:** Checks if the email exists and if the password matches the stored value.

### 3. Mobile Number Validator
* **Methods:** Includes two methods for validation:
    * **Standard Logic:** Checks if the input is 10 digits, numeric, and starts with 6, 7, 8, or 9.
    * **Regex Method:** Uses the `re` module with the pattern `r"^[6-9]\d{9}$"` for precise validation.

### 4. Palindrome Checker
* **Logic:** Checks if a given number reads the same forward and backward.
* **Implementation:** Uses mathematical logic (modulus and floor division) to reverse the number without converting it to a string.

## 🛠️ Technologies Used
* **Python 3.13.9**
* **Jupyter Notebook**
* **Regular Expressions (re module)**

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/Gaurav-1243/Python-Assignments.git](https://github.com/Gaurav-1243/Python-Assignments.git)
