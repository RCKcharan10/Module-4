# Experiment No: 4c Count Words in a File

## AIM  
To write a Python program to read a file and count the number of words in it.

---

## ALGORITHM  
1. Begin the program.  
2. Define a function `create_file(file_path, content)` that writes content into the given file.  
3. Define another function `count_words_in_file(file_path)` that reads the content from the file.  
4. Read input string from the user.  
5. Call `create_file()` with file path and input string.  
6. Call `count_words_in_file()` to count the number of words.  
7. Display the result.  
8. Terminate the program.

---

## 🧾 PROGRAM

```python
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def count_words_in_file(file_path):
    with open(file_path, 'r') as file:
        content = file.read()
    words = content.split()
    return len(words)

file_path = 'test_case_1.txt'
file_content = input()
create_file(file_path, file_content)
print('the no of words in the file is:', count_words_in_file(file_path))

```


### OUTPUT
![image](https://github.com/user-attachments/assets/074683e0-5a8d-4b62-879d-135bcc29fbcb)

### RESULT
Thus, the Python program to read a file and count the number of words in it has been implemented and executed successfully.
