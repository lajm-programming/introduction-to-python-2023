# Week Three Tasks

## Introduction to Python Classes

- We will learn how to create classes in Python
- We will learn how to create class attributes
- We will learn how to create class methods
- We will learn how to use classes in our code

## Vector Class

- We will write a vector class
- We will learn some Python magic methods

## Warming Up

## Problem 0: Python Dictionaries

(a)
Create an empty dictionary called **phone_book**, add to your dictionary the entries given below:

- Laima, +370-638-18259
- Tadas, +370-655-21007
- Kornelija,  +370-622-45451
- Aurimas, +370-615-12225
- Ernestas, +370-622-81599

(b)
Print your phone book in alphabetical order.

(c) 
Write a function called *phone_search()* that takes a phone book and name as parameters, 
and if the name is found in the phone book the function returns a string of the format "name: phone number",
if the name is not in the phone book, the function should return "Not found".

Example 1: If the name is "Laima", the function must return: "Laima=+370-638-18259"

Example 2: If the name is "Rokas", the function must return: "Not found"

(c) 
Test your function, trying it with different names.

(d)
You are ready to solve the "Day 8: Dictionaries and Maps" problem from the HackerRank, so go and solve it!


## Problem Solving

### Problem 1: Hero Backpack

We need to write a class that simulates a backpack functionality in a strategy game.

1) List of items that can be added to the backpack: medicine, gold, food

2) The backpack size is limited, so the total amount of all items can not exceed 30

3) Backpack attributes:

- content

5) Backpack methods:

- add_item(item_name, quantity)
- drop_item(item_name, quantity)
- list_items()

### Problem 2

In Python everything is an object, and in order to understand Python documentation 
we need to know how to work with classes.

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

### Problem 3

Mr. Anant is the manager at the INFINITY hotel. The hotel has an infinite amount of rooms.

One fine day, a finite number of tourists come to stay at the hotel.
The tourists consist of:
 - A Captain
 - An unknown group of families consisting of K members per group where K≠1
 

The Captain was given a separate room, and the rest were given one room per group.

Mr. Anant has an unordered list of randomly arranged room entries. 
The list consists of the room numbers for all of the tourists. The room numbers will appear K times per group 
except for the Captain's room.

Mr. Anant needs you to help him find the Captain's room number.
The total number of tourists or the total number of groups of families is not known to you.
You only know the value of and the room number list.

The room list is contained in the file **rooms.txt**
The very first number in the file represents the number of groups K.
(K=512)

Hint: You might need collections.Counter data structure in order to solve the problem

https://docs.python.org/3/library/collections.html#collections.Counter