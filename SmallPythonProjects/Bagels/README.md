# Bagels Game

![Bagels](https://raw.githubusercontent.com/lajmcourses/Images/master/bagels.jpeg)

Bagels is a deductive logic game, you must guess a secret three-digit number based on clues. 
The game offers one of the following hints in response to your guess: 

"Pico" when your guess has a correct digit in the wrong place.
When I say "Pico", I mean that one digit is correct but in the wrong position.

"Fermi" when your guess has a correct digit in the correct place.
When I say "Fermi", I mean that one digit is correct and in the right place.

"Bagels" if your guess has no correct digits. 
When I say "Bagels", I mean that no digit is correct

You have 10 tries to guess the secret number.

Example:

Guess #1: 123
- Pico

Guess #2: 456
- Bagels

Guess #3: 178
- Pico Pico

Guess #4: 791
 - Fermi Fermi

Guess #5: 701
 - You got it!

Do you want to play again? (yes or no)
- No

Thanks for playing!

## Assignment 

Write a program that imitates the game of Bagels.

1) When the program starts display the rules of Bagels.

````
    *** GAME OF BAGELS ********************************************************
    *                                                                         *
    *  I am thinking of a 3-digit number. Try to guess what it is.            * 
    *  Here are some clues:                                                   *
    *  When I say:    That means:                                             *
    *  Pico         One digit is correct but in the wrong position.           *
    *  Fermi        One digit is correct and in the right position.           * 
    *  Bagels       No digit is correct.                                      *
    *                                                                         *
    *  I have thought up a 3-digit number.                                    *
    *  You have 10 guesses to get it right.                                   * 
    *                                                                         *
    ***************************************************************************

````

2) Ask the user to guess the secret number.

````
    Enter a secret number: 
````

3) If the guess is correct, congratulate the user and end the game. 
If the guess is wrong provide user with the clues (as per rules of the game).

4) The game ends when the user makes a correct guess, or when the user uses 10 guess attempts.

5) After the game is over ask the user if he/she wants to play again.
