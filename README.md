# Data Analytics (DA) - Python Assignment 1
## Data Structures: Strings & Tuples

This repository contains the solution for Python Assignment 1, focusing on core Python data structures including **String operations** (concatenation, slicing, indexing, and built-in methods) and **Tuple manipulations** (creation, merging, repetition, and indexing).

---

## 📋 Table of Contents
- [Assignment Overview](#-assignment-overview)
- [Tasks & Implementation](#-tasks--implementation)
  - [Part 1: String Operations](#part-1-string-operations)
  - [Part 2: Tuple Operations](#part-2-tuple-operations)
- [Key Python Concepts Covered](#-key-python-concepts-covered)
- [How to Run](#-how-to-run)

---

## 🔍 Assignment Overview
The objective of this assignment is to demonstrate proficiency in handling text data and immutable sequences in Python. The workflow is split into two primary components:
1. **Dynamic Text Processing**: Ingesting user input, building a formatted welcome string, extracting substrings via slicing, and modifying text formatting.
2. **Sequential Data Management**: Creating numerical datasets using tuples, combining collections, and extracting specific subsets of elements.

---

## 💻 Tasks & Implementation

### Part 1: String Operations

#### 1. Concatenation
Combines a static greeting (`"Hello"`), a dynamically requested user name, and a standard language welcome message.
* **Input Example:** `Enter Your Name: Harsha`
* **Resulting String:** `"Hello Harsha, Welcome to Python Programming Language"`

#### 2. Slicing and Indexing
Performs extraction metrics on the concatenated greeting string:
* **First Character**: Extracts the initial index `[0]`.
* **Last Character**: Pinpoints the final character via negative indexing `[-1]`.
* **First 5 Characters**: Captures bounds using range slicing `[0:6]`.
* **Last 11 Characters**: Extracts trailing elements via slice notation `[-11:]`.
* **String Reversal**: Inverts the complete string sequence using step slicing `[::-1]`.

#### 3. Built-in String Methods
Manipulates a targeted text string (`strM = "Python beginner tutorial"`) using native string class attributes:
* `upper()`: Converts all characters to uppercase.
* `lower()`: Transforms all characters to lowercase.
* `capitalize()`: Capitalizes only the first letter of the sentence.
* `count('t')`: Quantifies occurrences of the substring character `'t'`.
* `replace()`: Swaps out targeted terminology (e.g., replacing `"Python"` with `"Data Analytics"`).

---

### Part 2: Tuple Operations

Given two baseline datasets:
* `Tup1 = (10, 20, 30)`
* `Tup2 = (40, 50, 60)`

The following operational tasks are implemented:
* **Concatenation (`t_combine`)**: Combines tuples into a unified sequence: `(10, 20, 30, 40, 50, 60)`.
* **Repetition**: Multiplies the dataset elements three times using the `*` operator.
* **3rd Element Access**: Retrieves the item at structural index `[2]`.
* **First Three Elements**: Slices the collection boundary from `[0:3]`.
* **Last Three Elements**: Extracts trailing sequence entries using `[-3:]`.

---

## 🧠 Key Python Concepts Covered
* **Immutability**: Understanding how tuples protect data records from accidental runtime alterations.
* **Sequence Slicing**: Mastered `[start:stop:step]` stride formulations to isolate data segments.
* **Streamlined Input Handling**: Utilizing `input()` interfaces for runtime parameter binding.
* **Method Chaining & In-Memory Operations**: Processing non-destructive transformations on variable data.

---

## 🚀 How to Run
1. Ensure you have **Python 3.x** installed on your system.
2. Clone or download the script file.
3. Open a terminal or command prompt and execute:
   ```bash
   python "Python Assignment 1.py"
   ```
4. Follow the interactive onscreen prompt to enter your name when requested.
