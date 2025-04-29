# Experiment No: 4d-Area of Circle using Class

## AIM  
To write a Python program that takes the radius from the user and finds the area of the circle using a class named 'pen' and a function named 'stationary'.

---

## ALGORITHM  
1. Begin the program.  
2. Define a class `pen` with a function `stationary(radius)` that calculates the area of the circle using the formula:  
   - `area = π * radius^2`
3. Read the radius of the circle from the user.
4. Create an instance of the `pen` class and call the `stationary()` function.
5. Print the area of the circle to the user, formatted to 2 decimal places.
6. Terminate the program.

---

## 🧾 PROGRAM

```python
import math

class pen:
    def stationary(self, radius):
        area = math.pi * radius * radius
        return area

radius = float(input())
circle = pen()
area = circle.stationary(radius)
print(f"Area of circle: {area:.2f}")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/eab62d6c-caf8-452d-a05f-e5e847d11828)

### RESULT
Thus, the Python program to calculate the area of the circle using a class and function has been implemented and executed successfully.
