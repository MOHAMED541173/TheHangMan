# # The Hanged Man Game

This is a simple implementation of the classic Hangman game using HTML, CSS, and JavaScript. Players try to guess the hidden word by selecting letters within a time limit and with a maximum of 5 wrong guesses before the man is hanged.

## Features

- Randomized word selection from a predefined list.
- A 30-second timer for each guess, reset after every correct letter.
- Players can make up to 5 incorrect guesses before the game ends.
- Visual feedback for correct and incorrect guesses:
  - Green buttons for correct guesses.
  - Red buttons for incorrect guesses.
- A dynamic hangman image that updates with each incorrect guess.

## Folder Structure


## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hanged-man-game.git
cd hanged-man-game



# The Hanged Man Game

This is a simple implementation of the classic Hangman game using HTML, CSS, and JavaScript. Players try to guess the hidden word by selecting letters within a time limit and with a maximum of 5 wrong guesses before the man is hanged.

## Features

- Randomized word selection from a predefined list.
- A 30-second timer for each guess, reset after every correct letter.
- Players can make up to 5 incorrect guesses before the game ends.
- Visual feedback for correct and incorrect guesses:
  - Green buttons for correct guesses.
  - Red buttons for incorrect guesses.
- A dynamic hangman image that updates with each incorrect guess.

## Setup

1. Clone the repository:
   git clone https://github.com/your-username/hanged-man-game.git
Navigate to the project folder:
cd hanged-man-game
Open the index.html file in your browser to play the game.

## How to Play
A random word is selected, and its letters are hidden.
Click the alphabet buttons to guess letters in the word.
If your guess is correct, the letter will be revealed, and the timer resets to 30 seconds.
If your guess is incorrect, the hangman image updates, and you lose one of your 5 chances.
The game ends when:
You reveal all letters in the word (win).
You run out of time or make 5 incorrect guesses (lose).
