# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:

# Reg.No: 212222210020
# Name: Prithisha S

n = int(input("Enter number of scores: "))
scores = list(map(int, input("Enter scores: ").split()))

scores = list(set(scores))
scores.sort(reverse=True)

print("Runner-up score:", scores[1])v

## OUTPUT

Enter number of scores: 5
Enter scores: 2 3 6 6 5
Runner-up score: 5

## RESULT

The programs were implemented successfully and the outputs were verified.
