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
```python
def dictionairy(): 
    # Create an empty dictionary
    key_value = {}    
    
    # Add key–value pairs
    key_value[2] = 56
    key_value[1] = 2
    key_value[5] = 12
    key_value[4] = 24
    key_value[6] = 18
    key_value[3] = 323
    
    print("Keys and Values sorted in ascending order by the value:")
    
    # Sort by value first (kv[1]), then by key (kv[0])
    sorted_items = sorted(key_value.items(), key=lambda kv: (kv[1], kv[0]))
    
    print(sorted_items)

dictionairy()
"""
d={2:56,1:2,5:12,4:24,6:18,3:323}
l=[]
for i in d:
    l.append(i)
l.sort()
print("Keys and Values sorted in alphabetical order by the key")
for i in l:
    print(tuple([i,d[i]]),end=" ")
"""
```

## Output
![Screenshot (146)](https://github.com/user-attachments/assets/5d91e8d6-c238-48b2-90d5-9ed7f0cd8874)

## Result
Thus,the program has been executed successfully.


