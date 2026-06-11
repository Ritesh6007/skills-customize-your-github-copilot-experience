
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python that uses strings, loops, conditionals, and user input to let players guess a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️ Create the Hangman game engine

#### Description
Write the core Hangman logic. Your program should select a secret word, show blanks for each letter, receive letter guesses, and update the displayed progress.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Display the current word progress with unguessed letters shown as `_`
- Accept one letter guess at a time
- Reveal correct letters when guessed

### 🛠️ Add game flow and win/lose conditions

#### Description
Add the remaining game loop and ending conditions so players can keep guessing until they win or run out of attempts.

#### Requirements
Completed program should:

- Track remaining incorrect guesses
- Ignore duplicate guesses without penalizing the player
- End with a win message when the full word is guessed
- End with a lose message and show the correct word when attempts are exhausted
