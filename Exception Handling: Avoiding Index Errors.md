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
```
list=[1,2,3,4,5]
try:
    print(list[5])
except IndexError:
    print("You're out of range")
```
## Output
<img width="1087" height="196" alt="image" src="https://github.com/user-attachments/assets/2d0ab8b4-892f-4548-a1d1-c92a84e90a70" />

## Result
Thus the program to write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is verified successfully.
