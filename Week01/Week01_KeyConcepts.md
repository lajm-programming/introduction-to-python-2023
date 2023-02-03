# Key Concepts

## Variables

Variable is one of the most important concepts in programming. 
You need to know and understand how to use variables in the computer programs.

## Data Types

There are seven main data types in Python that you have to be aware about:

- Number
- String
- Boolean
- List, 
- Tuple
- Dictionary
- Set

Simple types: number, string, boolean.

Collection types: list, tuple, dictionary, set

For starters, you need to know how to create each of the above-mentioned types. We will learn how to 
use each of them later in the course.


## Arithmetic Operations

- Addition: 3 + 2 = 5 
- Subtraction: 20 - 5 = 5
- Multiplication: 3 * 8 = 24
- Division: 100 / 10 = 10
- Exponentiation: 2**4 = 16
- Integer division: 15 // 4 = 3
- Modulo (or reminder): 14 % 4 = 2, 14 % 2 = 0


## Operations priority (PEMDAS)

Parentheses have the highest priority, then comes exponentiation, 
then follow multiplication, division, integer division and modulo,
addition and subtraction come last.


## For Loop

Loops are used for repeating things. The for loop is the most common way of repeating things in Python.

range() is often used together with the for loop. It defines how many times we will loop.

Example 1: Let's print 'Hello, World' three times

```python
for i in range(3):
    print('Hello, World!')
```

Example 2: Let's print the numbers from 25 to 30

```python
for i in range(25,  31):
    print(i)
```

## Comparison Operations

The result returned by any comparison operation is True or False

Equal: x == y

- 2 == 2 # True
- 2 == 3 # False


Not equal: x != y

- 2 != 2 # False
- 3 != 2 # True


Greater than: x > y

- 2 > 3 # False
- 3 > 2 # True


Greater than or equal to: x >= y

- 2 >= 3 # False
- 2 >= 2 # True
- 3 >= 2 # True


Less than: x < y

- 2 < 3 # True
- 3 < 2 # False


Less than or equal to: x <= y

- 2 <= 3 # True
- 2 <= 2 # True
- 3 <= 2 # False


## Logical Operations: and, or, not

True and True # True
True and False # False
False and True # False
False and False # False


True or True # True
True or False # True
False or True # True
False or False # False

not True # False
not False # True


## If Statement

Example 1: Student passes the test if his/her grade is greater than 70

```python
grade = 75

if grade > 70:
    print("You passed!")
```

Example 2:

```python
grade = 75

if grade > 70:
    print("You passed!")
else:
    print("You need to re-take the test before moving forwards.")
```

Example 3: If patient's body mass index is below 18.5, then the patient is underweighted; if patient's body mass
index is greater than or equal to 18.5 and less than 25, then the patient has a helthy weight; if patient's body mass
index is greater than or equal to 25 and less than 30, then the patient has an overweight; if patient's body mass 
index is greater than or equal to 30, then the patient is obess.

```python
bmi = 23

if bmi < 18.5:
    print("Underweight")
elif bmi >= 18.5 and bmi < 25:
    print("Healthy weight")
elif bmi >= 25 and bmi < 30:
    print("Overweight")
else:
    print("Obesity")

```