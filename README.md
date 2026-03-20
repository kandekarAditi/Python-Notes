<h3>🟢Introduction to Python:</h3>
   Python is a programming language used to give instructions to a computer.<br>
It is easy to learn because its syntax is simple like English.<br>
Computer understands only <b>binary (0 and 1)</b>, so Python code is converted using an interpreter.<br>
Python was created by <b>Guido van Rossum</b>.<br>

<h3>🟢Features and Uses of PythonL</h3>
<b>Features:</b><br>
1.Easy to read<br>
2.Less coding<br>
3.Free and open source<br>
4.Works on all systems<br>

<b>Uses:</b><br>
1.Web development<br>
2.AI & Machine Learning<br>
3.Data analysis<br>
4.Software development<br>

<h3>🟢Variables and Data Types:</h3>
Variable is used to store data.<br>
<b>Data Types:</b><br>
1.int → numbers (10, 20)<br>
2.float → decimal (10.5)<br>
3.str → text ("hello")<br>
4.bool → True/False<br>

<b>Example</b><br>
```python
name = "XYZ"
age = 21

<h3>🟢 Input and Output:</h3>
Input is taken from user using <b>input()</b><br>
Output is shown using <b>print()</b><br>

<b>User Input Example in Python</b><br>

```python
name = input("Enter your name: ")
print("Hello", name)
```

<h3>🟢Operators:</h3>
Operators are used to perform operations.<br>

<b>Types:</b><br>
1.Arithmetic → +, -, *, /<br>
2.Comparison → ==, >, <br>
3.Logical → and, or, not<br>

<b>Python Operators Example</b><br>
```python
a = 10
b = 5

print(a + b)
print(a > b)
```


<br>
<br>
<br>
<h3>OneExmaple for that above notes:</h3>
 🟢 Simple Python Example<br>

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))

print("Hello", name)
print("You are", age, "years old")

a = 10
b = 5

print("Addition:", a + b)           
print("a > b:", a > b)              
print("Age > 18:", age > 18)       
```

<h3>🟢Conditional Statements:</h3>
It used for decision making.<br>
It checks a condition and runs code based on <b>True or False.</b><br>
1.if<br>
2.else<br>
3.elif<br>

<h4>🔹1. if Statement:</h4>
Used to check a condition.<br>
<b>Syntax:</b><br>
### Syntax

```python
if condition:
    statement
```

### Example

```python
age = 18

if age >= 18:
    print("You can vote")
```

<h3>🔹2. if-else Statement:</h3>
Used when there are two choices.<br>
<b>Syntax:</b><br>
```python
if condition:
    statement1
else:
    statement2
```
<br>
<b>Example :</b><br>
```python
num = 10

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```
<h3>🔹2. elif Statement:</h3>

<b>Syntax:</b><br>
```python
if condition1:
    statement1
elif condition2:
    statement2
elif condition3:
    statement3
else:
    statement4
```
<b>Example :</b><br>
```python
marks = 75

if marks >= 90:
    print("Grade A")
elif marks >= 70:
    print("Grade B")
elif marks >= 50:
    print("Grade C")
else:
    print("Fail")
```

<h3>🧠 Homework</h3>
Q1)Write a Python program to check whether a number is even or odd using if-else.<br>
Q2)Write a Python program to find the largest among three numbers using if-elif-else.<br>
Q3)Write a Python program to check whether a year is a leap year or not.
<b>Hint:</b><br>
- Year divisible by 4 → Leap year  <br>
- But divisible by 100 → Not leap year<br>
- But divisible by 400 → Leap year<br>

