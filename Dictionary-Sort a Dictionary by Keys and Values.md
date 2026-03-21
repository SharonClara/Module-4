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

<img width="1068" height="317" alt="545474869-b6d6062b-8c9c-423b-b389-7fd81176bd83" src="https://github.com/user-attachments/assets/67383879-a978-4eba-9aa6-e1a19087641e" />



## Result

Thus, the program that sorts a dictionary's Keys and Values in alphabetical order was executed successfully.
