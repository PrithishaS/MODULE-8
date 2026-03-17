# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

# Reg.No: 212222210020
# Name: Prithisha S

students = {}

n = int(input("Enter number of students: "))

for _ in range(n):
    name = input("Enter name: ")
    marks = int(input("Enter marks: "))
    students[name] = marks

topper = max(students, key=students.get)

print("Topper:", topper)

## OUTPUT

Enter number of students: 3
Enter name: A
Enter marks: 80
Enter name: B
Enter marks: 90
Enter name: C
Enter marks: 85
Topper: B

## RESULT
The programs were implemented successfully and the outputs were verified.
