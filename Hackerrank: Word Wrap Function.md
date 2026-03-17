# 🔄 Hackerrank : # 📦 Python Word Wrap Function

This Python program defines a function that **wraps a long string into multiple lines**, ensuring each line does not exceed a specified width.

---

## 🎯 Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has **at most the given width**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Define a function `wrap(string, max_width)`:
   - Create an empty list `wrapped_lines` to store parts of the string.
   - Loop through the string using steps of `max_width`.
   - In each iteration, extract a substring of length `max_width`.
   - Append this substring to the list.
3. Join the list with `\n` to create the final string.
4. Return the result.
5. **End** the program.

---


## 🧪 Program
# Reg.No: 212222210020
# Name: Prithisha S

import textwrap

s = input("Enter string: ")
width = int(input("Enter width: "))

print(textwrap.fill(s, width))

## Output

Enter string: HelloWorldPython
Enter width: 5
Hello
World
Pytho
n

## Result
The programs were implemented successfully and the outputs were verified.

