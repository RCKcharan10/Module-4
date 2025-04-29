# Experiment No: 4a Create Dictionary of Squares

## AIM  
To write a Python program that creates a dictionary with integers from 1 to `n` as keys and their squares as values.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `create_square_dict(n)` that uses dictionary comprehension.  
3. Use a `for` loop with `range(1, n+1)` to generate keys.  
4. Assign each key’s value as its square.  
5. Return the dictionary.  
6. Read integer `n` from the user.  
7. Call the function with `n` and print the returned dictionary.  
8. Terminate the program.

---

### 🧾 PROGRAM

```python
def create_square_dict(n):
    return {i: i**2 for i in range(1, n+1)}

n = int(input())
result = create_square_dict(n)
print(result)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/e26eac2e-6b19-4969-976b-15d49dee3e46)

### RESULT
Thus, the Python program that creates a dictionary of squares from 1 to n has been implemented and executed successfully.
