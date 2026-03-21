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
It is like a container that holds information, and we can use or change it later.<br>

<h3>Rules of Variables</h3>
1. Variable name should start with a letter or underscore (_)<br>
2. Variable name cannot start with a number<br>
3. Only letters, numbers, and underscore are allowed<br>
4. No space allowed in variable name<br>
5. Variable names are case-sensitive<br>
6. Cannot use Python keywords as variable names
<br>
<br>
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

### Example:

```python
num = 10

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```
<h3>🔹2. elif Statement:</h3>
`elif` stands for "else if".<br>

It is used to check multiple conditions after an `if` statement.<br>  
If the first condition is false, Python checks the `elif` condition.<br>

If the `elif` condition is true, its block of code will execute.<br>

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

<h3>🧠Technical Questions (Practice)</h3>
Q1)Write a Python program to check whether a number is even or odd using if-else.<br>
Q2)Write a Python program to find the largest among three numbers using if-elif-else.<br>
Q3)Write a Python program to check whether a year is a leap year or not.<br>
<b>Hint:</b><br>
- Year divisible by 4 → Leap year  <br>
- But divisible by 100 → Not leap year<br>
- But divisible by 400 → Leap year<br>

<h3>🟢Loops:</h3>
Q)What are Loops?
Loops are used to execute a block of code repeatedly until a condition is satisfied.<br>
They help to reduce code repetition and make programs efficient.<br>

<b>Types:</b><br>
1.for loop<br>
2.While loop<br>

<h3>🔹1.For Loop</h3>
A `for` loop is used to iterate over a sequence (like list, string, range).<br>
- Used when number of iterations is known  <br>
- Works with list, tuple, string, range  <br>
- Simple and easy to use<br>

<b>Syntax:</b><br>
```python
for variable in sequence:
    statement
```
🟢 For Loop Example in Python <br>

```python
for i in range(1, 4):
    print("Python")
```
<h3>🔹2.While Loop</h3>
A `while` loop runs as long as the condition is true.<br>
- Used when number of iterations is unknown  <br>
- Runs based on condition  <br>
- Need to update condition (else infinite loop)<br>
<b>Syntax:</b><br><br>
`while condition: statement`
<br><br>
🟢While Loop Example in Python <br>

```python
i = 1

while i <= 3:
    print("Python")
    i += 1
```
<h3>🧠Loop Technical Questions (Practice)</h3>
1. Print numbers from 1 to 10 <br>
2. Print even numbers from 1 to 20<br>
3. Print sum of first 10 numbers<br>
4. Print multiplication table of a number (user input)<br>
5. Count numbers from 10 to 1 (reverse)<br>
6. Print all odd numbers between 1 to 50<br>
7. Find sum of digits of a number (e.g., 123 → 6)<br>
8. Check number is prime or not<br>
9. Print factorial of a number<br>
10. Print star pattern<br>
Example:<br>

*<br>
**<br>
***<br>
****<br>

<br>
<h3>Data Set</h3>
<h3>🟢 What is Data Set?</h3>
A data set is a collection of data or values.<br>
It can contain numbers, names, or any type of information grouped together.<br><br>
<h4>Example </h4>
1.Marks of students → [85, 90, 78, 92]<br>
2.Names of students → ["Rahul", "Neha"]<br>

These are called data sets.<br><br>
<h3>🟢 Data Sets in Python</h3>
In Python, we store data sets using:<br>
1.List<br>
2.Tuple<br>
3.Dictionary<br>
4.Set<br>

<h3>🟢 1. List</h3>
<h4>Q)What is List?</h4>
A list is used to store multiple values in one variable.<br>
It is <b>changeable</b> (mutable) and written using <b>square brackets [ ].</b><br>
-Ordered<br>
-Changeable (mutable)<br>
-Allows duplicate values<br>
🟢Example : <br>
```python
numbers = [10, 20, 30, 40]
print(numbers)
```
<br>
<h4>1.Access Value</h4>
```python
numbers = [10, 20, 30, 40]
print(numbers[0])
```
<br>
<h4>2.Change Value</h4>
```python
numbers = [10, 20, 30, 40]
numbers[1] = 50
print(numbers)
```
<br>
<h4>Common List Methods</h4>
 <b>🔹 append()</b><br>
Adds element at end<br>

```python
numbers = [10, 20, 30]
numbers.append(40)
print(numbers)
```
<br>
 <b>🔹 insert()</b><br>
Adds element at specific position<br>
```python
numbers = [10, 20, 30]
numbers.insert(1, 15)
print(numbers)
```
<br>
<b>🔹 remove()</b><br>
Removes specific value<br>
```python
numbers = [10, 20, 30]
numbers.remove(20)
print(numbers)
```
<br>
<b>🔹 pop()</b><br>
Removes last element<br>

```python
numbers = [10, 20, 30]
numbers.pop()
print(numbers)
```
<br>
<b>🔹 sort()</b><br>
Sorts list<br>

```python
numbers = [30, 10, 20]
numbers.sort()
print(numbers)
```
  <br>
  <b>🔹 reverse()</b><br>
Reverses list<br>

```python
numbers = [10, 20, 30]
numbers.reverse()
print(numbers)
```
<br>
<b>🔹 len()</b><br>
Find length<br>

```python
numbers = [10, 20, 30]
print(len(numbers))
```
<br>
<h3>🟢 Functions:</h3>
<b>Q)What is a Function?</b>
<br>
A function is a block of code that performs a specific task.<br>
We use functions to avoid repeating code.<br>

<b>*Simple: Function = reusable code</b><br>
<br>
<b>Q)Why use Functions?</b><br>
1.Avoids repetition<br>
2.Makes code easy to understand<br>
3.Saves time<br><br>

<b>Syntax:</b><br>
```python
def function_name():
    statement
```
<br>
🟢Example : <br>

def greet():<br>
    print("Hello Students")<br>
greet()<br>


<br>
<h3>🟢Function with Parameter </h3><br>
A function with parameter is a function that accepts input values.<br>
These values are called parameters and are used inside the function to perform operations.<br>
- Parameters are written inside parentheses  <br>
- Used to pass data to a function  <br>
- Makes function flexible and reusable <br>
<br>
🟢Example : <br>

def greet(name):<br>
    print("Hello", name)<br>
greet("XYZ")<br>

<br>
<h3>🟢Function with Return</h3>
A function with return sends a result back to the place where it was called.<br>
The `return` keyword is used to return the value.<br>
- `return` gives output from function  <br>
- Function stops after return  <br>
- Can store returned value in variable  <br><br>

Q)What is return keyword?<br>
The `return` keyword is used to send a value back from a function.<br>
- It gives output from the function  <br>
- It stops the function execution  <br>
- The returned value can be stored in a variable <br>

🟢Example : <br>

def add(a, b):<br>
    return a + b<br>
result = add(5, 3)<br>
print(result)<br>

Q)Difference between Parameter and Argument<br>

| Parameter | Argument |
|-----------|----------|
| Variable defined in function | Value passed to function |
| Written in function definition | Written in function call |
| Placeholder | Actual data |
| Example: `def greet(name)` | Example: `greet("Aditi")` |

<br><br>

<h3><b>Important Points:</b></h3>
1.def is used to create a function<br>
2.Function is called using function_name()<br>
3.Parameters are inputs<br>
4.return gives output<br>

<h3>🧠Function Technical Questions (Practice)</h3>
Q1) Check number Even or Odd<br>
Q2)Find Largest Number<br>
Q3)Factorial of Number<br>
Q4)Reverse a String<br>
