# 🔢 Even or Odd Number Checker

## 📄 Description

This Python program takes an integer input from the user and checks whether the number is **even** or **odd**. It demonstrates basic use of conditionals and user input in Python.

---

## 📌 Features

- Accepts user input
- Validates if the number is even or odd
- Uses Python’s modulus operator `%`
- Simple and beginner-friendly

---

## 💻 Code

```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(f"{num} is even")
else:
    print(f"{num} is odd")
