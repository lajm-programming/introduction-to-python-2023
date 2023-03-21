# Week03 Homework

DELIVERY DATE: 2023.03.27

## Assignment 1

a) Write a function that takes an integer as input and returns the sum of digits of an integer as an output.
The input number must be positive, and the number of digits of the input number should be in [1, 10] interval. 

b) Read the numbers from the file *test_numbers.csv* and compute the **sum_of_digits** for each number.
Display results on the screen. You need to display the input number and the result number.


Requirements:

1) Call you function **sum_of_digits**
2) Function must return an integer value that represents the sum of digits of an input number.

Examples:

Input value: 5
Output result: 5

Input value: 25
Output result: 7

Input value: 1234567
Output result: 28


## Assignment 2

Write a Student class with instance variables:

- student_id: int
- first_name: str
- last_name: str
- exam_scores: list[int]

The constructor takes student_id, first_name, and last_name in order to initialize the class.
The exam_scores must be initialized as an empty list.

and the methods:

- add_score(score): adds score to the list exam_scores. The score is any number in [0, 100]
- show_scores(): displays all student scores in one row
- score_average(): returns student's average score, or prints a message that the student didn't pass any exam yet
- course_passed(): if student collects three scores > 60, the method returns True, else method returns False

Test your program for students listed below: 

1, John, Doe, [100, 95]
2, Linda, Jones, [25, 65, 80, 75]
3, Jason, Kirk, [50, 60, 55]
4, Jane, Doe, [95, 80, 100]





