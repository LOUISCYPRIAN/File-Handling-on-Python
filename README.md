# File-Handling-on-Python
A beginner Python project demonstrating file handling concepts like reading, writing, and appending files with practical examples.


This repository contains simple and beginner-friendly examples of file handling in Python.

I created this project while learning how Python can interact with files instead of editing them manually.

## What I Learned

- How to read files using Python
- How to write and overwrite files
- How to append data to existing files
- How to automate repetitive tasks using code

## Examples Included

### 1. Read a File
```python
with open("file.txt", "r") as file:
    print(file.read())


Write to a File with open("file.txt", "w") as file:
    file.write("Hello World")

Append to a File  with open("file.txt", "a") as file:
    file.write("\nNew line added")

Write Multiple Lines   with open("file.txt", "w") as file:
    for i in range(100):
        file.write("I love myself\n")

```
- Why This Project Matters


Before this, I thought working with files meant editing them manually.

Now I understand that Python can automate file operations, which saves time and reduces errors especially when working with large data.

Tools Used

Python
Google Colab


Author
Cyprian Ogili
