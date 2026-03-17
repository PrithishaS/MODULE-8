# 🎓 Hackerrank:Python Program to Find Students with the Second Lowest Grade

This program reads student names and their corresponding grades, identifies the **second lowest grade**, and prints the names of all students who have that grade in **alphabetical order**.

---

## 🎯 Aim

To write a Python program to:
- Read a list of students and their grades.
- Identify the second lowest grade.
- Print the names of students who have that grade, sorted alphabetically.

---

## 🧠 Algorithm

1. **Read** an integer `n` representing the number of students.
2. **Read** each student’s name and grade, and store them as a sublist inside a list.
3. **Extract** all the grades and sort them.
4. **Identify** the second lowest grade from the sorted grade list.
5. **Collect** names of all students whose grade matches the second lowest grade.
6. **Sort** the names alphabetically.
7. **Print** each name on a new line.

---

## 💻  Program

# Reg.No: 212222210020
# Name: Prithisha S

students = []

for _ in range(int(input("Enter number of students: "))):
    name = input("Enter name: ")
    score = float(input("Enter score: "))
    students.append([name, score])

scores = sorted(set([s[1] for s in students]))
second_lowest = scores[1]

names = sorted([s[0] for s in students if s[1] == second_lowest])

for name in names:
    print(name)

## Output

Enter number of students: 3
Enter name: A
Enter score: 50
Enter name: B
Enter score: 40
Enter name: C
Enter score: 50
A
C

## Result

The programs were implemented successfully and the outputs were verified.

