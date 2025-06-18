# Sum of Numbers from 1 to 50

## 📄 Description

This is a simple Python program that calculates the sum of all integers from **1 to 50** using a `for` loop. It iteratively adds each number in the range and prints the final result.

---

## 📌 Features

- Uses a `for` loop for iteration.
- Calculates and prints the total sum.
- Demonstrates basic concepts of loops and accumulation in Python.

---

## 🧮 How It Works

1. Initializes a variable `total` to 0.
2. Iterates through the numbers from 1 to 50 using `range(1, 51)`.
3. Adds each number to `total`.
4. Prints the final sum using an f-string.

---

## 💻 Code

```python
total = 0

for i in range(1, 51):
    total += i

print(f"The sum of numbers from 1 to 50 is: {total}")
