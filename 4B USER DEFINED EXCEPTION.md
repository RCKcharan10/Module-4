# Experiment No: 4b User Defined Exception for Number Guessing

## AIM  
To write a Python program that raises a user-defined exception for the guessing number problem where the user has to guess the number 10.

---

## ALGORITHM  
1. Begin the program.  
2. Define the target number (10).  
3. Read an integer input from the user.  
4. Use `try-except` to handle exceptions.  
5. If the entered number is greater than 10, raise an exception with message "This value is too large, try again!".  
6. If it is equal to 10, print "Congratulations! You guessed it correctly.".  
7. If it is less than 10, print "This value is too small, try again!".  
8. Print the exception message in the `except` block.  
9. Terminate the program.

---

## 🧾 PROGRAM

```python
a = int(input())

try:
    if a > 10:
        raise Exception("This value is too large, try again!")
    elif a == 10:
        print("Congratulations! You guessed it correctly.")
    else:
        print("This value is too small, try again!")
except Exception as e:
    print(e)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/11ca81a6-afe7-4492-afe8-52501a719217)

### RESULT
Thus, the Python program to raise a user-defined exception for the guessing number problem has been implemented and executed successfully.
