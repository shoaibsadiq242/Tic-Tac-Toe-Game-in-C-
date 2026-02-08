# Tic-Tac-Toe Game

A simple console-based Tic-Tac-Toe game implemented in C++ for two players.

---

## Features

* Two-player gameplay (X and O)
* Interactive numbered grid in the console
* Input validation to prevent invalid moves
* Win detection for rows, columns, and diagonals
* Draw detection when the board is full
* Replay option to start a new game
* Clear ASCII board display

---

## Prerequisites

* C++ compiler (GCC, Clang, or MSVC)
* Terminal or command prompt

---

## How to Run

```bash
# Clone the repository
git clone <your-repo-link>
cd <repository-folder>

# Compile the program
g++ main.cpp -o tictactoe

# Run the program
./tictactoe      # Linux / Mac
tictactoe.exe    # Windows
```

---

## How to Play

* The board positions are numbered 1-9:

```
 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9
```

* Players take turns entering a number to place their mark
* Player 'X' goes first, followed by Player 'O'
* First player to get 3 marks in a row (horizontally, vertically, diagonally) wins
* If all squares are filled with no winner → draw
* After each game, you can choose to play again or exit

---

## Project Structure

* `main.cpp` – contains all game logic

### Key Functions

* `displayBoard()` – displays the current board
* `placeMark()` – places a mark for the current player
* `checkWin()` – checks if the current player has won
* `checkDraw()` – checks for a draw
* `switchPlayer()` – switches turns between X and O
* `resetBoard()` – resets the board for a new game

---

## License

This project is open source and available for educational and personal use.

---

## Author

Shoaib
