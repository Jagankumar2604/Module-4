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
```
count = 0
with open("story.txt", "r") as file:
    for line in file:
        if line.strip() and not line.lstrip().startswith('T'):
            count += 1
print("Sum :", count)

```

## Output
<img width="395" height="167" alt="502987690-51b25bda-3717-4183-aa6f-b3fa7e0284bf" src="https://github.com/user-attachments/assets/08aecaf7-b205-4cc1-a6f1-8bcd59069b16" />


## Result
Thus,Python program that counts the number of lines in a text file `story.txt` that do not start with the alphabet `'T'' is executed successfully.
