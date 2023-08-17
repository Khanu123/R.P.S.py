# R.P.S.py
Importing the random Module:
The random module in Python provides functions for generating random numbers. In this game, the computer's choices are generated using the random module.

Initializing Variables:
The variables user_wins and computer_wins are initialized to keep track of the number of wins for the user and the computer, respectively.

Defining Options:
The options list contains the possible choices in the game: "rock", "paper", and "scissors".

Game Loop:
The while True: loop is the core of the game. It keeps running until the player decides to quit by typing "q". Inside the loop, the following steps occur:

a. User Input:
The player is prompted to type their choice ("rock", "paper", "scissors") or "q" to quit. The input is converted to lowercase to ensure case-insensitive comparisons.

b. Quitting:
If the user types "q", the loop breaks and the game ends.

c. Validating User Input:
If the user input is not one of the valid options ("rock", "paper", "scissors"), the loop continues, prompting the user for input again.

d. Computer's Choice:
A random number between 0 and 2 is generated using random.randint(0, 2). This number corresponds to the index of the options list, and it determines the computer's choice.

e. Comparing Choices:
The user's choice and the computer's choice are compared to determine the winner. Depending on the combinations of choices, either the user or the computer wins. If the user wins, their win count (user_wins) is incremented. If the computer wins, the computer's win count (computer_wins) is incremented.

f. Displaying Results:
The game prints out the computer's choice and whether the user won or lost the round.

Game Summary and Goodbye:
After the user decides to quit the game, the loop ends. The game then displays the total number of wins for both the user and the computer and says goodbye.

This code showcases the basic concepts of user input, random number generation, conditional statements, loops, and tracking scores in a simple rock-paper-scissors game. It's a great example for understanding how programming logic can be used to create interactive games.
