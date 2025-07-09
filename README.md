# Data Structures Course Projects

This repository contains **three independent mini-projects** developed for the *Data Structures* course.  
Each phase/project is located in a separate folder, along with its corresponding documentation (PDF file).  
You can read the description in each folder to understand the goal and scope of that specific project.

---

## Phase 1 – To-Do List Manager

In this project, a simple **To-Do List** system is implemented with the following features:

- User account creation and login
- Create and manage multiple task lists
- Add, edit, and delete tasks
- Search for tasks by keyword
- Sort task lists based on different criteria
- Console-based interface (no GUI)

---

## Phase 2 – Infix Calculator

This phase includes the implementation of a **basic arithmetic calculator** with the following capabilities:

- Parses and evaluates simple arithmetic expressions such as:
  
  **Example Input:**  
  `4+2 + 2^2 - 1`  
  **Postfix Conversion:**  
  `4 2 + 2 2 ^ + 0 1 1 * - +`  
  **Result:**  
  `9.0`

- Logical validation of expressions:
  - Checks for balanced parentheses
  - Ensures correct operator/operand sequence
- Handles special edge cases like **negative numbers**
- Converts infix expressions to **postfix (Reverse Polish Notation)** using the `infixToPostfix()` function
- Calculates and returns the final result using stack-based evaluation

---

## Phase 3 – Console Social Network

In this phase, a **console-based mini social media** platform (inspired by Instagram) was developed with features such as:

- User account creation, login, and deletion
- Public and private profiles with appropriate access rules
- Posting text-based posts
- Following and unfollowing users
- Messaging system (send/view messages)
- Profile customization
- Marking posts as favorite
- Search functionality

> The application runs entirely in the **console window of your IDE**, with user interaction handled via text-based menus and inputs.

---

## General Notes

- All texts, labels, and variable names are written in **Finglish** (Persian using Latin alphabet).  
For example: `"vorod"` instead of `"login"` or `"ezafe"` instead of `"add"`.
- Each phase is **independent** and has its own folder and instructions.
- All user interaction is handled in the **IDE console**, no GUI is used.
- **Important**: In all projects, be sure to search for the keyword `"save"` using `Ctrl + F`, and update any file paths according to your local directory.

---

## Final Note

These projects are aimed to help students—especially those majoring in **Computer Engineering**—gain a better understanding of data structure concepts in a practical and hands-on way.

**We hope this repository proves useful in your learning journey. Best of luck!**
