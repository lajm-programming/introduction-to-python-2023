# Week Two Tasks

## Lesson 01: Git and GitHub

- We will learn the basics of working with Git and GitHub
- We will install and configure Git on our local machines
- We will upload the Week01 homework projects to the Github

### Preparing projects for GitHub

1) Each homework project needs to be in a separate directory 
2) We have two projects: CurrencyConverter and MultiplicationGame


## Warm Up Exercise

**Fizz Buzz** is a game for children to teach them division. Players take turns to count
incrementally, 

- replacing any number divisible by 3 with the word **Fizz**;
- replacing any number divisible by 5 with the word **Buzz**;
- replacing any number divisible by 3 and 5 with **Fizz Buzz**;

If none of the conditions above holds, the number is named as is.

*Assignment 1:*

Write a function, that when given an integer n

- if n is divisible by 3 returns "Fizz"; 
- if n is divisible by 5 returns "Buzz"; 
- if n is divisible by 3 and 5 returns "Fizz Buzz"; 
- if nothing of the above holds, the function retuns n.


*Assignment 2:*

Write a program that outputs the first 25 Fizz Buzz numbers.


## Lesson 02: Strings

### Typical Problems

Solve problem from the HackerRank '30 Days of Code'

Day 5: Loops

Day 6: Let's Review

### Learn Something New:

Companies often try to personalize their offers to make them more attractive. One simple
way to do this is just to insert the person’s name at various places in the offer. Of course,
companies don’t manually type in every person’s name; everything is computer-generated.
Write a program that asks the user for their name and then generates an offer like the one
below. For simplicity’s sake, you may assume that the person’s first and last names are one
word each.

Email example:

```text
Dear George Washington,
I am pleased to offer you our new Platinum Plus Rewards card
at a special introductory APR of 47.99%. George, an offer
like this does not come along every day, so I urge you to call
now toll-free at 1-800-314-1592. We cannot offer such a low
rate for long, George, so call right away.
```

Your task is to write a function that takes user first name and last name, and generates
a personalized email like the one you see above.

Use Python template strings to solve this problem:

https://docs.python.org/3/library/string.html#template-strings


## Lesson 03: Lists

### Problem 01:

Write a program that asks the user to enter a list of integers. Do the following:
(a) Print the total number of items in the list.
(b) Print the last item in the list.
(c) Print the list in reverse order.
(d) Print the sum of the elements of the list.
(e) Print the average of the elements of the list


### Problem 02:

Write a function that takes a list as an input argument and returns a modified list.
The modified list should be constructed as follows:

- all the values less than 20 must be replaced with False
- all the values equal to 20 must be left as is
- all the values greater than 20 must be replaced with True


### Problem 03:

Solve the problem Nested Lists from the HackerRank: https://www.hackerrank.com/challenges/nested-list/problem


## Lesson 06: Dictionaries

### Problem 01: Create a Simple Dictionary

Create a dictionary storing an information about the person, the dictionary has to contain the following data:

- First Name
- Last Name
- Age
- Occupation
- Hobbies (list 2 or 3),
- City
- Country

### Problem 02: Favourite Programming Language

We have a student poll data with favourite programming languages:

programming_languages = {
    "Linas": "Ruby",
    "Petras": "C++",
    "Jurga": "Python",
    "Nerijus": "Java"
}

a) Process the dictionary and print out the following sentence for every entry of the dictionary:

<StudentName> favourite programming language is <ProgrammingLanguage>.

Example: Linas programming language is Ruby.

!!! The sentences should follow students names alphabetical order. !!!

b) There is a list of students, some of students had participated in the poll, and some didn't.

students_list = ["Paulius", "Nerijus", "Alina", "Jurga", "Linas"]

If the student participated in the poll print: Hi <StudentName>, thank you for taking part in our Programming Language poll!

If the student didn't participat in the poll print: Hi <StudentName>! What is your favourite programming language?

## Lesson 05: While Loops

### Problem 01:
The code below prints the numbers from 1 to 50. Rewrite the code using a while loop to
accomplish the same thing.

```python
for i in range(1,51):
    print(i)
```

### Problem 02: 

Write a program that allows the user to enter any number of test scores. The user indicates
they are done by entering in a negative number. Print how many of the scores are A’s (90 or
above). Also print out the average.

### Problem 03: Logging In

Write a program that asks the user to enter a password. If the user enters the right password,
the program should tell them they are logged in to the system. Otherwise, the program
should ask them to reenter the password. The user should only get five tries to enter the
password, after which point the program should tell them that they are kicked off of the
system.
