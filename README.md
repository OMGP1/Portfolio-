# Data Science & Python Portfolio

Welcome to my personal learning and project repository! This portfolio is a comprehensive documentation of my journey in acquiring data science skills. It begins with the fundamentals of Python programming, moves into essential data science libraries, and culminates in an end-to-end data analysis project.

## 📚 Table of Contents
1.  [About This Repository](#-about-this-repository)
2.  [Part 1: Python Fundamentals](#-part-1-python-fundamentals)
3.  [Part 2: Core Data Science Libraries](#-part-2-core-data-science-libraries)
4.  [Part 3: Featured Project – CodeBook Social Network Analysis](#-part-3-featured-project--codebook-social-network-analysis)
5.  [Key Skills Overview](#-key-skills-overview)

---

## 📖 About This Repository

This repository is structured to mirror my learning path. Each section builds upon the previous one, demonstrating a methodical approach to mastering data science. The goal is to not only learn the tools but also to understand how to apply them to solve real-world problems.

---

## 🐍 Part 1: Python Fundamentals

This section contains a series of Jupyter notebooks covering the core concepts of Python required for data science.

* **`01_python_basic.ipynb` & `02_strings.ipynb`**: Introduction to Python syntax, variables, and string manipulation.
* **`03_operators.ipynb` & `05_operator_precedence.ipynb`**: Covers arithmetic, comparison, and logical operators, along with the rules of precedence.
* **`04_input.ipynb`**: Working with user input.
* **`06_if_else.ipynb` & `07_match_case.ipynb`**: Control flow using conditional statements.
* **`08_f-strings.ipynb`**: Modern and efficient string formatting.
* **`09_loops.ipynb`**: `for` and `while` loops for iteration and flow control.
* **`10_lists.ipynb`**: In-depth exploration of lists, Python's versatile, mutable sequence.
* **`11_tuples.ipynb`**: Working with tuples, Python's immutable sequence.
* **`12_sets.ipynb`**: Understanding and using sets for handling unique, unordered collections.
* **`13_dict_methods.ipynb`**: Deep dive into dictionary methods for key-value pair manipulation.
* **`14_file_handling.ipynb`**: Reading from and writing to files.
* **`15_json.ipynb`**: Serializing and deserializing data using the JSON format.
* **`16_oops.ipynb`**: Introduction to Object-Oriented Programming, including classes, objects, and principles.
* **`17_list_comprehensions.ipynb`**: Writing concise and readable list-based operations.
* **`18_lambda.ipynb`**: Creating anonymous functions for short, simple operations.

---

## 📊 Part 2: Core Data Science Libraries

This section focuses on the hands-on application of NumPy and Pandas, the foundational libraries for data analysis in Python.

### NumPy
* **`Creating_numpy_arrays.ipynb`**: Demonstrates various ways to create NumPy arrays.
* **`Numpy-Data-Types.ipynb`**: Explores the different numerical data types available in NumPy and how to use them.
* **`indexing-and-Slicing.ipynb`**: Covers techniques for accessing and modifying elements in 1D NumPy arrays.
* **`Multidimensional-Indexing-and-Axis.ipynb`**: Expands on indexing and slicing for multi-dimensional arrays, including the concept of an axis.
* **`Speedtest.ipynb`**: A practical comparison that illustrates the significant performance advantage of NumPy's vectorized operations over standard Python lists for numerical computations.

### Pandas
* **`Core Data Structures.ipynb`**: Introduces the `Series` (1D) and `DataFrame` (2D), the primary data structures in Pandas, using `data.csv`.
* **`Creating DataFrames.ipynb`**: Shows multiple methods for creating a DataFrame from scratch.
* **`Data-Selection-Filtering.ipynb`**: Provides a practical guide to selecting and filtering data from a DataFrame using boolean indexing, multiple conditions (`&`, `|`), and the `.isin()` method, demonstrated with the `data for filtering.csv` file.

---

## 📂 Part 3: Featured Project – CodeBook Social Network Analysis

This project serves as a capstone, integrating the skills from the previous sections to deliver a complete data product. It demonstrates a full data workflow from ingestion and cleaning to feature engineering and analysis.

### Objective
To analyze a raw data dump from a fictional social media platform for coders, "CodeBook". The core tasks were to clean the raw data and then build two key recommendation features from scratch, using **only pure Python**.

### Project Workflow & Files
1.  **`01_Introduction.ipynb`**: Loaded and explored the initial, clean dataset (`data.json`) to understand its structure.
2.  **`02_data_cleaning.ipynb`**: Took a messy, raw dataset (`data2.json`) and performed crucial cleaning operations:
    * Removed users with empty or missing names.
    * Eliminated duplicate friend entries from user profiles.
    * Filtered out inactive users with no connections.
    * Deduplicated the `pages` list to ensure unique entries.
    * Saved the clean output to `cleaned_data2.json`.
3.  **`03_people_you_may_know.ipynb`**: Developed a "People You May Know" recommendation algorithm. This feature suggests new friends to a user by identifying "friends of friends" and ranking them by the number of mutual connections. Tested at scale with `massive_data.json`.
4.  **`04_pages_you_might_like.ipynb`**: Created a "Pages You Might Like" feature that recommends pages to a user based on common interests shared with other users on the platform.

---

## 🏆 Key Skills Overview

| Category                | Skills & Technologies                                                              |
| ----------------------- | ---------------------------------------------------------------------------------- |
| **Programming Language**| **Python** (Advanced)                                                              |
| **Data Science Libraries**| **Pandas**, **NumPy** |
| **Core Concepts** | Data Cleaning, Data Wrangling, Data Structures, Algorithmic Thinking, OOP, File I/O  |
| **Data Formats** | **JSON**, **CSV** |
