# Hangman Game

This is a simple command-line implementation of the classic word guessing game, Hangman.

## Features

- **Word Selection:** A random word is chosen from a pre-defined list of words for the player to guess.
- **User Input:** Players can input a single letter guess with each turn.
- **Display:** The game displays a visual representation of the Hangman as the player makes incorrect guesses.
- **Feedback:** Players are informed whether their guess is correct or not, and how many lives they have left.
- **Win/Lose Conditions:** The game ends when the player correctly guesses the word or runs out of lives.

## How to Play

1. **Run the Game:** Execute the `hangman.py` script using a Python interpreter.
2. **Guess a Letter:** Input a letter to guess.
3. **Guess Again:** If the guessed letter is incorrect, the player loses a life. The Hangman visual representation updates accordingly.
4. **Win or Lose:** If the player correctly guesses all letters in the word, they win. If they run out of lives, they lose.

## Dependencies

- Python 3.x

## Acknowledgments

- The words for the game are provided by the `hangman_words` module.
- ASCII art for the Hangman stages is provided by the `hangman_art` module.
