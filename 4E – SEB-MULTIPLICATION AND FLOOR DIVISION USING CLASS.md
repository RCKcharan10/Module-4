# Experiment No: 4e – SEB-Multiplication and Floor Division Using Class and Conditional Statements

## AIM  
To write a Python program using class and conditional statements to perform multiplication and floor division based on user choice.

---

### ALGORITHM  
1. Define a class `CSE` with the following methods:  
   - `setvalues(a, b)` to set instance variables.  
   - `mul()` to return the multiplication of `a` and `b`.  
   - `div()` to return the floor division result of `a` by `b`.  
2. Create an object of the `CSE` class.  
3. Read two integer inputs from the user and set them using `setvalues()`.  
4. Start an infinite loop.  
5. Read the user’s choice:  
   - If choice is `1`, call `mul()` and display result.  
   - If choice is `2`, call `div()` and display result.  
   - If choice is `0`, display “Exiting!” and break the loop.  
   - For any other input, print “invalid choice”.  
6. Terminate the program.

---

### 🧾 PROGRAM

```python
class CSE:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def mul(self):
        return self.a * self.b

    def div(self):
        return self.a // self.b

n = CSE()
a = int(input())
b = int(input())
n.setvalues(a, b)

while True:
    c = int(input())
    if c == 1:
        res = n.mul()
        print(f"Result:  {res}")
    elif c == 2:
        res = n.div()
        print(f"Result:  {res}")
    elif c == 0:
        print("Exiting!")
        break
    else:
        print("invalid choice")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/ec015c1d-4088-4892-8482-a583d75d52a9)

### RESULT
Thus, the Python program using class and conditional statements to perform multiplication and floor division has been implemented and executed successfully.

markdown
Copy code
