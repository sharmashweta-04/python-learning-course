# 📂 Chapter 13 - Advanced Python 2

<div align="center">

[![Status](https://img.shields.io/badge/Status-Not%20Started-lightgrey?style=for-the-badge)](#)
[![Files](https://img.shields.io/badge/Files-0-blue?style=for-the-badge)](#)

---

This chapter covers environmental isolation via virtual environments, dependency export, functional programming constructs (`lambda`, `map`, `filter`, `reduce`), and advanced string formatting.

</div>

## 📓 Core Topics Covered
* **Virtual Environments**: Isolated environments (`venv`) to manage project-specific dependencies independently.
  * *pip freeze*: Generates a list of installed dependencies for `requirements.txt`.
* **Lambda Functions**: Anonymous, single-expression functions created using the `lambda` keyword.
* **String Join Method**: Join elements of an iterable into a single string using a separator.
* **String Format Method**: Old format rendering tool (pre-f-strings) to inject variables into strings.
* **Functional Programming Tools**:
  * `map(func, iter)` — Applies a function to all elements in an iterable.
  * `filter(func, iter)` — Filters elements out of an iterable using a predicate function.
  * `reduce(func, iter)` — Performs rolling computation on sequential pairs of elements in an iterable (from `functools`).

---

## 📝 Practice Exercises (Planned)
* [ ] Create a virtual environment, activate it and install packages
* [ ] Use `requirements.txt` to duplicate packages into a second virtual environment
* [ ] Format a student profile containing name, marks, and phone number using `.format()`
* [ ] Filter a list of numbers to select only those divisible by 5 using a lambda function
* [ ] Find the maximum number in a list using the `reduce()` function
* [ ] Run a flask application inside a virtual environment (if applicable)
