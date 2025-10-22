# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))

## Output
<img width="495" height="214" alt="Screenshot 2025-10-22 205930" src="https://github.com/user-attachments/assets/b1f8f0c1-08b5-47b3-846d-91c256655666" />

## Result
Thus the program runs successfully.
