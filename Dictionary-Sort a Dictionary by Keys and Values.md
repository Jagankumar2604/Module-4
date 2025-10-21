# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d={2:56,1:2,5:12,4:24,6:18,3:323}
l=[]
for i in d:
    l.append(i)
l.sort()
print("Keys and Values sorted in alphabetical order by the key")
for i in l:
    print(tuple([i,d[i]]),end=" ")


```

## Sample Output
<img width="1270" height="378" alt="502987347-78369094-19ce-441b-9964-41099067227c" src="https://github.com/user-attachments/assets/5812ce08-7b1d-4d08-be94-254fb6ce5425" />


## Result
Thus the program that sorts a dictionary's Keys and Values in alphabetical order is executed successfully


