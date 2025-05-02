# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```python
Reg.No
Name
Add Your Code Here
grades_input = input("Enter grades separated by commas: ")
grades_list = grades_input.split(',')
try:
    numbers = [int(g.strip()) for g in grades_list]
    print("Grades as numbers:", numbers)
except:
    print("The grades you entered were in an invalid format.")
    print("What you entered:", grades_list)
```

### OUTPUT

![Screenshot 2025-05-02 122155](https://github.com/user-attachments/assets/72534fe8-9024-42fd-9656-441a797fd2c8)


### RESULT
Thus, the program executed successfully and the output is verified.
