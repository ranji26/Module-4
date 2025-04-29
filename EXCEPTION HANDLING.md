# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
write a python program for the solution of value error in exception handling and check whether the number is even or odd.

---

### ALGORITHM

1. Prompt User: Ask the user to input a number.

2.Try Block:

Convert the input to an integer using int().

Use % 2 to check if the number is even or odd.

3.Except Block:

If conversion fails (e.g., input is "abc"), catch the ValueError and display an error message.

4.Output:

Print whether the number is even or odd, or show an error message for invalid input.

---

### PROGRAM
def digit():  <br>
    try:   <br>
        a=int(input())   <br>
        if(a%2==0):   <br>
            print("You entered even number")  <br>
        else:   <br>
            print("An odd number")   <br>
    except:   <br>
        print("Enter only number")   <br>
digit()

### OUTPUT

![image](https://github.com/user-attachments/assets/b2a1c619-e03f-4026-8c71-e94feb0c2e70)


### RESULT
Thus,the program for the solution of value error in exception handling and check whether the number is even or odd was implemented and executed successfully.
