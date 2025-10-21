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
my_dict = {'b': 25, 'a': 10, 'd': 30, 'c': 20}
sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="1505" height="228" alt="image" src="https://github.com/user-attachments/assets/ef4fb9d2-6b83-4f68-bc5b-49cba35d4a42" />

## Result
Thus the program To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order
is verified successfuly.
