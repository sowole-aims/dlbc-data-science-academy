---
layout: page
title: Assignments
description: A feed containing all of the class assignments.
---

# Assignments

---
title: Assignment 1
---

## Python Basics

### Objective

In this assignment, you will get hands-on experience with Python's fundamental concepts, including your first program, data types, expressions, variables, and string operations.

### Submission Method

Submit your completed assignment as a Python Jupyter Notebook using Google Colab. 

To get started with Google Colab, visit the [Colab website](https://colab.research.google.com/) and create a new notebook where you can complete your assignment. You should save your notebook with your solutions and submit the notebook file for evaluation to the instructor.

### Assignment Tasks

#### Task 1.1: Your First Program

Write a Python program that prints "Hello, World!" to the screen.

#### Task 1.2: Types

Write Python code to:

- a. Declare and print an integer variable.
- b. Declare and print a float variable.
- c. Declare and print a boolean variable.
- d. Declare and print a string variable.

#### Task 1.3: Expressions and Variables

Write Python code to:

- a. Calculate and print the result of 5 raised to the power of 3.
- b. Calculate and print the result of the expression 7 * (5 + 2).
- c. Declare two variables x and y with values 10 and 20, respectively. Swap their values and print the result.

#### Task 1.4: String Operations

Write Python code to:

- a. Create a string variable containing your full name and print it.
- b. Print the length of your full name string.
- c. Extract your first name and last name from the full name string and print them separately.

{% for assignment in site.assignments %}
{{ assignment }}
{% endfor %}
