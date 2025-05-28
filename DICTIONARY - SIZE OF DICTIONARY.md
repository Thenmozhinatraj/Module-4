# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```python
#Reg.No 212223060291
#Name Thenmozhi N
#Add Your Code Here
from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3} 

dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}

dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print(f"Size of dic1: {getsizeof(dic1)}bytes")
print(f"Size of dic2: {getsizeof(dic2)}bytes")
print(f"Size of dic3: {getsizeof(dic2)}bytes")
```

### OUTPUT

![image](https://github.com/user-attachments/assets/e97adca9-c8e3-4636-8e3c-d4f5dbbe207e)

### RESULT
Thus, the program executed successfully and the output is verified.
