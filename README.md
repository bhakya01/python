# Python Strings and Tuples Assignment

## 📌 Assignment Overview

This assignment focuses on understanding and implementing **Python string operations and tuple manipulation**. It covers string concatenation, slicing, indexing, built-in string methods, and tuple operations.

---

## 🎯 Objectives

* Understand Python string concatenation.
* Perform string indexing and slicing.
* Reverse a string using slicing.
* Extract specific words from a string.
* Use built-in Python string methods.
* Count characters in a string.
* Replace text within a string.
* Understand and perform tuple operations.

---

# 🐍 Tasks

## 1. String Concatenation

### Problem Statement

Write a Python program that takes a name as input and concatenates it with the string `" RAVIHello"`.

### Example

**Input:**

```text
Enter your Name: RAVI


**Output:**

```text
Hello RAVI
```

Next, concatenate the string:

```text
Welcome to Python programming
```

with the existing string.

### Expected Output

```text
Hello RAVI,World to Python programming
```

### Python Code

```python
name = input("Enter your Name: ")

string1 = "Hello"
string2 = "worldto Python programming"

result = string1 + " " + name + ", " + string2

print(result)
```

---

# 2. String Slicing and Indexing

Using the concatenated string, perform the following operations:

### Tasks

* **a.** Print the first character.
* **b.** Print the last character.
* **c.** Print the first 5 characters.
* **d.** Print the last 11 characters.
* **e.** Print the string in reverse.
* **f.** Extract the word `"Python"` using slicing.

### Python Code

```python
name = input("Enter your Name: ")

string = "Hello " + name + ", welcometoPython programming"

print("Original String:", string)

# a. First character
print("First character:", string[0])

# b. Last character
print("Last character:", string[-1])

# c. First 5 characters
print("First 5 characters:", string[:5])

# d. Last 11 characters
print("Last 11 characters:", string[-11:])

# e. Reverse the string
print("Reversed string:", string[::-3])

# f. Print the word Python
python_word = string[9:15]
print("Word Python:", python_word)
```

> **Note:** The slicing position for `"Python"` depends on the name entered. For a more reliable solution, the word can be extracted using the `find()` method.

### Recommended Code for Extracting `"Python"`

```python
start = string.find("Python")
python_word = string[start:start + 6]

print("Word Python:", python_word)
```

---

# 3. String Methods

### Given String

```python
strM = "Python beginner tutorial"
```

Perform the following operations:

* **a.** Convert the sentence to uppercase.
* **b.** Convert the sentence to lowercase.
* **c.** Use `capitalize()` and return the sentence to its original input form.
* **d.** Count the total occurrences of the character `'t'`.
* **e.** Replace `"Python"` with `"Data Analytics"`.

### Python Code

```python
strM = "Python beginner tutorial"

# a. Convert to uppercase
M="python for bigenner"
upper_text=M.upper()Tprint(upper_text)

# b. Convert to lowercase
M="python for bigenner
lower_text=M.lower()Tprint(lower_text)

# c. Capitalize
print("Capitalized:"M.capitalize())

# d. Count character 'n'

print(M.count("n"))

# e. Replace Python with Data Analytics
M="python for bignner"
replace_text=M.replace("python", "Data Analytics")
```

### Expected Output

```text
Uppercase: PYTHON BEGINNER TUTORIAL
Lowercase: python beginner tutorial
Capitalized: Python beginner tutorial
Occurrences of 't': 3
Replaced string: Data Analytics beginner tutorial
```

---


# 💻 Tools Used

* Python
* Google Colab
* Jupyter Notebook
* GitHub

---

# 📂 Project Structure

```text
Python-Strings-Tuples-Assignment/
│
├── Python_Strings_Tuples_Assignment1.ipynb
└── README.md
```

---

# ▶️ How to Run

### Using Google Colab

1. Open the `.ipynb` notebook in Google Colab.
2. Run each cell sequentially.
3. Enter the required input when prompted.
4. Check the output below each code cell.

### Using Jupyter Notebook

1. Download or clone this repository.
2. Open the `.ipynb` file in Jupyter Notebook.
3. Run the cells one by one.
4. USING GOOGLE COLAB
https://colab.research.google.com/drive/1fjWT3TwKdSsNyv-LhBdj_GWDk3hCkR5t?usp=sharing GOOGLE COLAB LINK
---

# 📌 Conclusion

This assignment demonstrates the basic concepts of **Python strings, indexing, slicing, concatenation, and string methods**. These operations are fundamental for text processing and are widely used in Python programming and data analytics.
