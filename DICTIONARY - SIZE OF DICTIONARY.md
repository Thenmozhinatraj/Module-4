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
import sys
dic1 = {1: "a", 2: "b"}
dic2 = {"name": "Alice", "age": 25, "city": "Paris"}
dic3 = {}
print(f"Size of dic1: {sys.getsizeof(dic1)} bytes")
print(f"Size of dic2: {sys.getsizeof(dic2)} bytes")
print(f"Size of dic3: {sys.getsizeof(dic3)} bytes")
```

### OUTPUT

![Screenshot 2025-05-02 121731](https://github.com/user-attachments/assets/01220514-c5cc-4759-a21b-6a4ff3bc95b0)

### RESULT
Thus, the program executed successfully and the output is verified.
