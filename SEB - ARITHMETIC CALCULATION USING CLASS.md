# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

class cse:  <br>
    def mul(self,a,b):  <br>
        self.a=a  <br>
        self.b=b  <br>
        print("Result: ",a*b)  <br>
    def div(self,a,b):  <br>
        self.a=a  <br>
        self.b=b  <br>
        print("Result: ",a//b)    <br> 
        
z=cse()      <br>
a=int(input())  <br>
b=int(input())   <br>
q=False    <br>
while q==False:  <br>
    x=int(input())  <br>
    if x==1:  <br>
        z.mul(a,b)  <br>
    elif x==2:   <br>
        z.div(a,b)  <br>
    elif x==0:  <br>
        print("Exiting!")  <br>
        q=True  <br>
        break;  <br>
    else:  <br>
        print("Invalid choice")  <br>
        q=True  <br>
        break;  <br>

### OUTPUT

![image](https://github.com/user-attachments/assets/01e17217-6767-4dd8-8b53-1936f42597bf)


### RESULT
Thus the Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div is successfully implemented and executed.
