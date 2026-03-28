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

## 🧾 Program:
```
# Program to count lines not starting with 'T'

count = 0

with open("story.txt", "r") as file:
    for line in file:
        if not line.startswith('T'):
            count += 1

print("Number of lines not starting with 'T':", count)
```
## Output:

<img width="727" height="253" alt="image" src="https://github.com/user-attachments/assets/a2e34971-e16d-4b3e-bdd0-cdd51dc5b56c" />

## Result:

Thus, the Python program to count the number of lines in a file that do not start with 'T' was successfully executed and verified.
