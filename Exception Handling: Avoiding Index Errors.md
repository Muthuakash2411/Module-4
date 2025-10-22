# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
try:
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)
except IndexError:
    print("check index range")


## Output
<img width="1196" height="305" alt="Screenshot 2025-10-22 205751" src="https://github.com/user-attachments/assets/d89bbfd6-f71f-45c5-83af-b55727d4b7e9" />

## Result
Thus the program runs successfully.
