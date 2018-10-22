# Assignment 18

For this assignment you will use `while` loops to make a number guessing game.

## Specifications

* Ask the user for the range (inclusive) of the numbers (minimum and maximum). Then generate a random number in that range (refer to the Assignment 13 Github page for help on this).
* Start the game by asking for a guess. You should either say they are correct, too high, or too low and let them guess again.
* When they finally get it correct tell them how many guesses they made. You should also tell them if they entered an invalid number.

Please use two classes for this program. Your main game logic should not be in the Runner.

### Sample Outputs

```
Enter the min: 0
Enter the max: 100

Enter your guess: 79
You got it! It took 1 guess.
```

```
Enter the min: 25
Enter the max: 1000

Enter your guess: 500
Too high.
Guess again: 400
Too low.
Guess again: 409
You got it! It took 3 guesses.
```

```
Enter the min: 50
Enter the max: 500

Enter your guess: 100
Too high.
Guess again: 50
Too low.
Guess again: 5
Invalid guess.
Guess again: 80
You got it! It took 3 guesses.
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

