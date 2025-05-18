# 🎲 Number Guessing Game
Can you guess the number? 🎯 A fun command-line game that gives you hints until you win!

A simple number guessing game written in Python. The user sets an upper limit, and the program picks a random number within that range. The player keeps guessing until they get it right!

## 🕹️ How It Works

1. The game prompts the user to enter a number — this becomes the upper limit of the guessing range.
2. The program randomly selects a number between 0 and the chosen upper limit (exclusive).
3. The user makes repeated guesses, and the game provides hints:
   - "You were above the number!" if the guess is too high.
   - "You were below the number!" if the guess is too low.
4. Once guessed correctly, the game celebrates and displays how many attempts it took.

## 🧠 Features

- Input validation for both the range and guesses.
- Tracks number of attempts.
- Friendly prompts and hints.
- Fun emojis for celebration! 🥳🎊

## 🛠 Requirements

- Python 3.x

## 🚀 How to Run

1. Make sure Python is installed.
2. Download or clone this repository.
3. Open a terminal and run:

```bash
python "Number guessing game.py"
