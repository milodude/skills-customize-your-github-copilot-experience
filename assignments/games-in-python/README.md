# 📘 Assignment: Games in Python

## 🎯 Objective

Build a Hangman-style word game to practice Python fundamentals including strings, loops, conditionals, and user input. By the end, students should be able to structure game logic and provide clear feedback to players.

## 📝 Tasks

### 🛠️ Build Core Game Logic

#### Description
Create the base Hangman game flow. The program should choose a secret word, accept player guesses one letter at a time, and update the displayed progress after each guess.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list.
- Display the hidden word using underscores (for example, `_ _ _ _`).
- Ask the player to guess one letter per turn.
- Reveal correctly guessed letters in all matching positions.
- Prevent crashes from invalid input such as empty guesses.

### 🛠️ Track Attempts and End States

#### Description
Add rules for incorrect guesses and clear game-ending behavior. The game should stop when the word is solved or when the player runs out of attempts.

#### Requirements
Completed program should:

- Track remaining incorrect guesses and update the count after wrong letters.
- Show letters already guessed so the player can avoid repeats.
- End with a win message if the full word is guessed.
- End with a lose message if attempts reach zero, and reveal the secret word.
- Include at least one short sample game interaction in comments or output documentation.
