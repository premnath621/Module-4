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

## 🧪Program:
```
# Program to sort dictionary by keys and values

# Original dictionary
d = {'b': 'banana', 'a': 'apple', 'c': 'cherry'}

# Sort by keys
sorted_keys = dict(sorted(d.items()))

# Sort by values
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

# Output
print("Original dictionary:", d)
print("Sorted by keys:", sorted_keys)
print("Sorted by values:", sorted_values)
```

## Sample Output:

<img width="819" height="220" alt="image" src="https://github.com/user-attachments/assets/695196fa-99cc-4140-8c9f-87912d9a1ed6" />


## Result:

Thus, the Python program to sort a dictionary by keys and values was successfully executed and verified.
