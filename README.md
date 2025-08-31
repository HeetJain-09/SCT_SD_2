# SCT_SD_2
Repository containing software development TASK 2
-------------------------
### SkillCraft Technology Internship Task
 This repository contains a project completed during my internship as a Software Development Intern at SkillCraft Technology. 
 
 This task focuses on enhancing my skills in Python programming, logic building, and basic user input handling.

--------------------------
## Task 02: Number Guessing Game

A Python program that generates a random number between 1 and 100 and challenges the user to guess it within a limited number of attempts.

The program gives feedback after each guess and includes input validation for a seamless user experience.
---------------------------------------
## How the Game Works
- The program generates a random number in the range 1 to 100.

- The user has up to 10 attempts to guess the number.

- After each guess, feedback is provided:

 - "Too low! Try again." if the guess is lower than the number.

 - "Too high! Try again." if the guess is higher than the number.

 - "Congratulations!" message if guessed correctly (also shows the attempt count).

- Handles invalid (non-integer) input with a helpful message.
- If 10 attempts are used without guessing correctly, the correct number is revealed.
 
  -----------------
  ## Features
1. Random number generation between 1 and 100.

2. The user has a maximum of 10 attempts to guess the number.

3. Input validation with error handling for non-integer inputs (using try-except).

4. Informs user if all attempts are used and reveals the number.

5. Tracks the number of attempts taken to guess correctly.Simple and clean command-line interface.
6. This project is built using only core Python libraries (random).




------------------------------
## How to Run
- Ensure Python is installed.

- Run the script:
python SC_SD_2.py
- Follow the prompts to enter your guesses.
------------------------------------
## Sample Output

Welcome to the Guess the Number game!

I've chosen a number between 1 and 100.

You have 10 attempts to guess it.

Enter your guess: 40

Too low! Try again.

Enter your guess: 80

Too high! Try again.

Enter your guess: 60

Too low! Try again.

Enter your guess: 72

Congratulations! You guessed the number 72 in 4 attempts
