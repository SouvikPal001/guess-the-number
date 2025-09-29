# Number Guessing Game

A simple Python console game where the player tries to guess a randomly generated number within a chosen range.

The game begins by asking the player to "Type a number:" to set the maximum range. It then displays all numbers from 0 to that number. The player makes guesses, and the game gives feedback:

- If the guess is too low, it says "You were below the number!"
- If the guess is too high, it says "You were above the number!"
- If the guess is correct, it says "You got it!" and shows how many guesses it took.

For example, if the player sets the range to 10:
```text
Type a number: 10  
Your range of numbers is:  
0  
1  
2  
3  
4  
5  
6  
7  
8  
9  
10  
Make a guess: 5  
You were below the number!  
Make a guess: 8  
You were above the number!  
Make a guess: 7  
You got it!  
You got it in 3 guesses!
```
This game is great for learning basic Python concepts like loops, conditionals, user input validation, and random number generation.

## Features

- Handles invalid input gracefully.
- Tracks the number of guesses.
- Provides dynamic feedback based on the guess.
- Simple, interactive console-based gameplay.
