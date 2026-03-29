 

## 1️⃣ Simple Calculator

This calculator can **add, subtract, multiply, and divide**.

```python
# Simple Calculator
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Cannot divide by zero"
    return a / b

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == '1':
    print("Result:", add(num1, num2))
elif choice == '2':
    print("Result:", subtract(num1, num2))
elif choice == '3':
    print("Result:", multiply(num1, num2))
elif choice == '4':
    print("Result:", divide(num1, num2))
else:
    print("Invalid choice")
```

✅ **Concepts used:** functions, if-else, input, type conversion, error checking.

---

## 2️⃣ Student Record System

Store **multiple students** and view their information.

```python
# Student Record System
students = []

def add_student():
    name = input("Enter student name: ")
    age = input("Enter age: ")
    department = input("Enter department: ")
    student = {"name": name, "age": age, "department": department}
    students.append(student)
    print("Student added successfully!\n")

def view_students():
    if not students:
        print("No students found.\n")
        return
    for i, student in enumerate(students, start=1):
        print(f"{i}. Name: {student['name']}, Age: {student['age']}, Department: {student['department']}")
    print()

while True:
    print("1. Add Student")
    print("2. View Students")
    print("3. Exit")

    choice = input("Enter choice: ")
    if choice == '1':
        add_student()
    elif choice == '2':
        view_students()
    elif choice == '3':
        break
    else:
        print("Invalid choice\n")
```

✅ **Concepts used:** lists, dictionaries, functions, loops, input/output.

---

## 3️⃣ Simple Login System

Check a **predefined username and password**.

```python
# Simple Login System
users = {
    "leta": "1234",
    "admin": "adminpass"
}

username = input("Enter username: ")
password = input("Enter password: ")

if username in users and users[username] == password:
    print("Login successful! Welcome,", username)
else:
    print("Invalid username or password")
```

 
