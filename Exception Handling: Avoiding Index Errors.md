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
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")

```
## Output
<img width="998" height="302" alt="545475046-a5e4b753-e4af-4b35-93b5-0934d0bc12df" src="https://github.com/user-attachments/assets/d56a7002-bcfd-43ee-b9c9-59c7c9b40ed1" />




## Result
Thus, the program was executed successfully.
