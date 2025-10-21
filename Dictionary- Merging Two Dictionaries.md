## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'b': 200, 'd': 40, 'e': 50}
def merge(d1, d2):
    merged_dict = {**d1, **d2}  
    return merged_dict
result = merge(dict1, dict2)
print("Merged Dictionary:", result)
```

## Output
<img width="1505" height="228" alt="image" src="https://github.com/user-attachments/assets/635d994c-f6f3-458d-8984-e5032aabd09f" />

## Result
Thus the program To write a Python program that merges **two dictionaries** and combines their key-value pairs is verified successfully.
