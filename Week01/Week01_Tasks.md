# Week One Tasks

## Setup

1) Install Python on your computer: https://www.python.org/

2) Install PyCharm Community on your computer: https://www.jetbrains.com/pycharm/download/

3) Create GitHub Account: https://github.com/

4) Send your GitHub account link to v.alisauskaite@lajm.lt

5) Create HackerRank account. Tyr using the following format when naming the account:
firstname_lastname. For example, the person named John Doe has to create the account john_doe. 

6) Send your HackerRank account username to v.alisauskaite@lajm.lt


## Lesson 01: Variables

### Problem 1: Weight Converter

(a) Write a program that asks the user for a weight in kilograms and converts it to pounds. 

(b) Write a program that asks the user for a weight in pounds and converts it to kilograms. 

Hint: There are 2.2 pounds in a kilogram.

### Problem 2: Simple Computations

Write a program that asks the user to enter three numbers (use three separate input state-
ments). Create variables called total and average that hold the sum and average of the
three numbers and print out the values of total and average .

Test Cases:

- Input 1: 10, 20, 30. Output: total=60, average=20
- Input 2: 2.8, 4.5, -2.7. Output: total=4.6, average=1.533
- Input 3: 128, 327, 98. Output: total=553, average=184.333

### Problem 3: Tip Calculator

Write a tip calculator. Ask the user for the price of the meal and
the percent tip they want to leave. Then print both the tip amount and the total bill with the
tip included.

Round the total bill amount as follows:

If the calculated amount is 10.98, then the total bill amount should be 11.00.

If the calculated amount is 10.82, then the total bill amount should be 10.90

Test Cases:

- Input 1: meal_price=10.00 , tip = 10 %. Output: 11.00
- Input 2: meal_price: 8.54, tip = 5 %. Output: 9.00
- Input 3: meal_price: 162.89, tip = 7%. Output: 174.30

## Lesson 02: Data Types

- Number
- String
- Boolean
- List, tuple
- Dictionary
- Set


## Lesson 03: For Loops 

### Problem 4

a) Write a program that prints the elements of the list.

List: ["Dan", "Linda", "Jonas", "Simona", "Michael"]


b) Find the index of the first occurrence of "Jonas". What is the value of the index? Access "Jonas" by index. 

c) How can be accessed the last element of the list?

### Problem 5

a) Write a program that prints keys and values of the dictionary.

Dictionary:

```text
{
    "Dan": 98,
    "Linda": 90
    "Jonas": 60
    "Simona": 65
    "Michael": 80
}
```

b) Write a function that finds students that collected a top score. The top score is 100.

c) Write a function that returns the highest score received.

## Lesson 04: Logical Statements

### Problem 6:

Ask the user to enter a temperature in Celsius. The program should print a message based
on the temperature:
• If the temperature is less than -273.15, print that the temperature is invalid because it is
below absolute zero.
• If it is exactly -273.15, print that the temperature is absolute 0.
• If the temperature is between -273.15 and 0, print that the temperature is below freezing.
• If it is 0, print that the temperature is at the freezing point.
• If it is between 0 and 100, print that the temperature is in the normal range.
• If it is 100, print that the temperature is at the boiling point.
• If it is above 100, print that the temperature is above the boiling point.

### Problem 7: Body Mass Index

Body Mass Index (BMI) is computed as follows

```text
BMI = Weight,kg / (Height,m * Height,m)
```

BMI Ranges:

- below 18.5: underweight
- 18.5 - 25: healthy weight
- 25 - 30: overweight range
- 30 and more: obesity

Write the program in Python that does the following things

(a) asks the user to enter height in meters, and weight in kg;

(b) computes person's body mass index; 

(c) displays it on the screen;

(e) prints the conclusion based on BMI range;