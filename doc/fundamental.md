Python fundamentals are the core building blocks you must understand before writing real-world programs. I’ll explain them clearly with simple examples so you can apply them immediately.

---

# 🧠 1. Variables & Data Types

Variables store data. Python is dynamically typed (no need to declare type).

```python
# Variables
name = "Leta"
age = 22
height = 1.75
is_student = True

print(name, age, height, is_student)
```

### Common Data Types

```python
# String
text = "Hello"

# Integer
num = 10

# Float
price = 19.99

# Boolean
is_valid = False
```

---

# ➕ 2. Operators

Used to perform operations.

```python
# Arithmetic
a = 10
b = 3

print(a + b)  # 13
print(a - b)  # 7
print(a * b)  # 30
print(a / b)  # 3.33

# Comparison
print(a > b)   # True
print(a == b)  # False

# Logical
print(a > 5 and b < 5)  # True
```

---

# 🔀 3. Conditional Statements (if-else)

Used for decision making.

```python
age = 18

if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")
```

### Multiple conditions

```python
score = 75

if score >= 90:
    print("A")
elif score >= 70:
    print("B")
else:
    print("C")
```

---

# 🔁 4. Loops

### for loop

```python
for i in range(5):
    print(i)
```

### while loop

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

# 📦 5. Lists (Arrays)

Ordered collection of items.

```python
fruits = ["apple", "banana", "mango"]

print(fruits[0])  # apple

# Add item
fruits.append("orange")

# Loop through list
for fruit in fruits:
    print(fruit)
```

---

# 🔑 6. Dictionaries

Store key-value pairs.

```python
student = {
    "name": "Leta",
    "age": 22,
    "department": "Software Engineering"
}

print(student["name"])
```

---

# 🧩 7. Functions

Reusable block of code.

```python
def greet(name):
    return "Hello " + name

print(greet("Leta"))
```

### Function with default parameter

```python
def add(a, b=5):
    return a + b

print(add(3))  # 8
```

---

# 📥 8. Input & Output

```python
name = input("Enter your name: ")
print("Welcome,", name)
```

---

# 📂 9. Basic File Handling

```python
# Write to file
with open("test.txt", "w") as file:
    file.write("Hello World")

# Read file
with open("test.txt", "r") as file:
    content = file.read()
    print(content)
```

---

# ⚠️ 10. Error Handling

```python
try:
    num = int(input("Enter number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
```

---

# 🚀 Summary

Python fundamentals include:

* Variables & data types
* Operators
* Conditionals (`if`, `else`)
* Loops (`for`, `while`)
* Data structures (lists, dictionaries)
* Functions
* Input/output
* File handling
* Error handling

---

 
