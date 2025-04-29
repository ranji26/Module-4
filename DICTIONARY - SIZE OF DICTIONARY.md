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

import sys  <br>
dic1 = {"A": 1, "B": 2, "C": 3}   <br>
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}   <br>
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}   <br>
print(f"Size of dic1: {sys.getsizeof(dic1)}bytes")   <br>
print(f"Size of dic2: {sys.getsizeof(dic2)}bytes")    <br>
print(f"Size of dic3: {sys.getsizeof(dic3)}bytes")

### OUTPUT

![image](https://github.com/user-attachments/assets/2b26e8ee-99d7-4166-b4e1-0a5a497350ce)


### RESULT
Thus,the program to print the size of a dictionary using getsizeof() from the sys module was implemented and executed successfully.
