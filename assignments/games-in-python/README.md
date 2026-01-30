# 📘 Assignment: Games in Python

## 🎯 Objective

Build a playable Hangman game to practice strings, loops, conditionals, and user input while managing game state.

## 📝 Tasks

### 🛠️ Game Setup and Word Selection

#### Description
Create the basic game structure and choose a secret word from a predefined list.

#### Requirements
Completed program should:

- Store a list of possible words in a Python list.
- Randomly select one word at the start of the game.
- Track remaining attempts with a starting number (for example, 6).

### 🛠️ Player Guessing Loop

#### Description
Implement a loop that lets the player guess letters and shows their progress.

#### Requirements
Completed program should:

- Ask the user to enter a single letter each turn.
- Display current progress using underscores for unknown letters (e.g., `_ a _ _ e`).
- Update the progress display when a correct letter is guessed.
- Decrease remaining attempts when a guessed letter is not in the word.

### 🛠️ Win/Lose Conditions

#### Description
End the game when the player wins or runs out of attempts.

#### Requirements
Completed program should:

- Detect when all letters are revealed and display a win message.
- Detect when attempts reach zero and display a lose message with the word.
- Stop the loop when the game ends.
# 🎮 Hangman Game Challenge

Build the classic word-guessing game using Python strings, loops, and user input.

## � What You'll Build

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

**Skills practiced:** String manipulation, loops, conditionals, random selection

## ✅ Must Have's

Your game must:
- Randomly select words from a predefined list
- Accept letter guesses and show current progress (_ _ _ format)
- Track incorrect guesses remaining
- End when word is guessed or attempts exhausted
- Display win/lose messages
