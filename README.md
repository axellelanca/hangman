# Hangman Game

This is a classic Hangman game implemented in Go. The game selects a random word, and the player tries to guess the word by guessing individual letters.

## Features

* **Random word selection:** The game chooses a random word from a predefined list.
* **Limited number of attempts:** The player has a limited number of incorrect guesses.
* **Letter guessing:** The player guesses the word by entering one letter at a time.
* **Game progress display:** The game displays the current state of the word, with correctly guessed letters revealed and unguessed letters hidden.
* **Error handling:** The game handles invalid input and duplicate letter guesses.
* **Game over:** The game ends when the player either guesses the word correctly or runs out of attempts.

## How to Play

1. Clone the repository
```
git clone https://github.com/axellelanca/hangman
```

2. Navigate to the project directory:
```
cd hangman
```

3. Run the game:
```
go run main.go
```
4. The game will start, and you will be prompted to guess a letter.

5. Enter a letter and press Enter.

6. The game will update the display, showing your progress and the remaining attempts.

7. Continue guessing letters until you either guess the word or run out of attempts.


## Screenshots

<img width="688" alt="Screenshot 2025-05-03 at 15 30 08" src="https://github.com/user-attachments/assets/0f6b9292-242b-4bc6-aa89-de4d4be00153" />

<img width="596" alt="Screenshot 2025-05-03 at 15 31 54" src="https://github.com/user-attachments/assets/d580aede-0fb2-42af-b372-59fe6f489018" />

<img width="592" alt="Screenshot 2025-05-03 at 15 34 02" src="https://github.com/user-attachments/assets/563cb0d6-dd95-4d97-89b8-6f31463729ac" />


## Improvements
* Add more words to the file.
* Add difficulty levels.
* Implement a scoring system.
* Add a "play again" option.
* Add a two-player mode.

