# Tic-Tac-Toe Game

This is a simple **Tic-Tac-Toe** game implemented in Python. The game is played in the console and supports two players (X and O) taking turns to mark spaces on a 3x3 grid.

## Features

- Two-player gameplay
- Displays the Tic-Tac-Toe board after every move
- Detects and announces the winner
- Identifies when the game ends in a draw
- This prevents players from selecting an already occupied spot
- Allows restarting the game after it ends

## How to Play

1. Run the Python script.
2. The game starts with **X** making the first move.
3. Players take turns entering a position (0-8) to place their mark.
4. The game checks for a winner after every move.
5. If a player wins, the game announces the winner.
6. If the board is full with no winner, the game declares a draw.
7. Players have the option to restart or exit after a game ends.

## Installation

No additional dependencies are required. Just run the script using Python:

```bash
python tic_tac_toe.py
```

## Example Gameplay

```
Welcome to Tic Tac Toe
X's Turn
Please enter a value (0-8): 0
X | 1 | 2
--|---|--
3 | X | 5
--|---|--
6 | 7 | X
...
X won the match!
Game Over!
Do you want to play again? (y/n):


