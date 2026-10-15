# Number Guessing Game

A simple command-line game built in Python. The computer picks a secret number between 1 and 100, and you have 5 attempts to guess it.

## How it works

1. The computer picks a random number between 1 and 100.
2. You get 5 attempts.
3. After each guess, the game tells you if your guess is too high or too low.
4. If you guess correctly, you win and the game ends.
5. If you run out of attempts, the game ends and reveals the secret number.

## Concepts used

- `random.randint()` to generate the secret number
- A `while` loop to repeat the game until attempts run out
- `if / elif / else` to compare the guess to the secret number
- `break` to stop the loop early when the player wins
- `input()` and `int()` to take and convert the player's guess

## How to run

1. Make sure Python 3 is installed.
2. Download `number_guessing_game.py` (or open the notebook in Google Colab).
3. Run it:

```
python number_guessing_game.py
```

## Example

```
Guess the number 1 to 100: you have 5 attempts: 72
LOWER!
Guess the number 1 to 100: you have 4 attempts: 60
LOWER!
Guess the number 1 to 100: you have 3 attempts: 30
HIGHER!
```

## Possible improvements

- Let the player choose the number range
- Add a "play again" option
- Handle invalid input (like typing letters instead of a number)

## Author

Chijioke Omeifejideofor
