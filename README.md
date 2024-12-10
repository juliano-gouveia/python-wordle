# Wordle - Terminal Version

A simple terminal-based implementation of the popular game **Wordle** using Python. This version of Wordle is played in the terminal/command line and allows you to guess a 5-letter word within 6 attempts.

## Features

- **Single File**: The entire game is implemented in a single Python file (`wordle.py`).
- **Wordle Rules**: Guess the correct 5-letter word in 6 tries or fewer.
- **Color Feedback**: Get feedback for each guess with color-coded hints:
  - Green: Correct letter and correct position.
  - Yellow: Correct letter, wrong position.
  - Red: Incorrect letter.
- **Word List**: The game uses a predefined list of valid 5-letter words used by wordle.

## Requirements

- Python 3.x (Tested with Python 3.12+)
- No external dependencies are required.

## How to Play

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/juliano-gouveia/python-wordle.git
   ```
2. Navigate to the repository directory:
   ```bash
   cd wordle-terminal
   ```
3. Run the game:
   ```bash
   python3 wordle.py
   ```
