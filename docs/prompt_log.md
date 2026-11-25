# AI Coding Assistant Practicum – Prompt Documentation

**Project:** Student Expense Splitter CLI

**AI Coding Assistant:** Cursor AI

**Programming Language:** Python

## 1. Zero-shot Prompt

```text
Act as an experienced Python developer.

Create a Student Expense Splitter CLI application from scratch using Python.

The application should allow users to:
1. Add students.
2. Record shared expenses.
3. Divide expenses equally among students.
4. Calculate how much each student owes.
5. Display the final balances.
6. Handle invalid inputs and missing student names.

Use functions and classes wherever appropriate.
Write clean, beginner-friendly Python code with proper comments and docstrings.

Create a modular project structure and include basic unit tests.

Do not use any external paid APIs or services.
```

## 2. Few-shot Prompt

```text
Act as a Python developer. Improve the Student Expense Splitter application by implementing consistent input validation and error messages.

Follow these examples:

Example 1:
Input: Expense amount = -500
Expected Output: "Error: Expense amount must be greater than zero."

Example 2:
Input: Student name = ""
Expected Output: "Error: Student name cannot be empty."

Example 3:
Input: Expense amount = 1000, Participants = 4
Expected Output: "Each student owes Rs. 250."

Example 4:
Input: Participant count = 0
Expected Output: "Error: At least one participant is required."

Now implement these validation rules in the project.

Use the same error message style as the examples.
Keep the existing project structure and avoid changing unrelated functionality.

Add unit tests for all validation cases.
```

## 3. Chain-of-thought Prompt

```text
Act as a senior Python debugging engineer.

Analyze the Student Expense Splitter application and identify potential logical errors in expense calculation and balance settlement.

Consider this edge case:

Three students participate in shared expenses:
- Student A pays Rs. 900.
- Student B pays Rs. 300.
- Student C pays Rs. 0.

The total expense is Rs. 1200, and each student should contribute Rs. 400.

Think step by step. Explain how the total expense, individual share, and each student's balance should be calculated.

Identify any errors in the existing implementation, explain their root causes, and suggest corrections.

Then implement the necessary fixes and write unit tests to verify the calculations.

Do not modify unrelated parts of the application.
```

**Note:** These are the planned prompts. Add the actual Cursor responses, screenshots, and evaluations after performing each interaction.
