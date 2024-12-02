# Connect Four Game

A simple, two-player **Connect Four** game implemented in Python using the **Pygame** library. The game allows two players to take turns to drop their pieces (Red and Yellow) into a grid. The goal is to connect four of your pieces in a row, column, or diagonal.

## Features

- **Two-player gameplay**: Players alternate turns to drop pieces into the grid.
- **Visual display**: The game board is drawn using **Pygame** and updates dynamically as players make their moves.
- **Winning condition**: The game checks for a winning move after every turn, and announces the winner when a player connects four pieces in a row, column, or diagonal.
- **Game over screen**: A message displays the winner and the game ends after the win.

## Installation

### Prerequisites

To run this project, you need to have Python installed along with the Pygame library. You can install **Pygame** using `pip`:

```bash
pip install pygame
```

## Clone the repository

Clone this repository to your local machine using:

```bash
git clone https://github.com/Bhoomikapm0116/connect-four.git
```
## Running the Game
Navigate to the project directory:

```bash
cd src.py
```

Run the game:

```bash
python src.py
```
The game window will appear, allowing you to start playing immediately.

## How to Play

- **Player 1 (Red)** and **Player 2 (Yellow)** take turns to click on a column to drop their pieces into the grid.
- The objective is to connect four of your pieces either vertically, horizontally, or diagonally.
- The game will announce the winner once a player wins and then stops accepting further moves.

## Game Controls

- **Mouse**: Use the mouse to hover over the columns to see a preview of where the piece will land. Click on the column to drop the piece.
- **Quit the game**: Close the game window or press the exit button to quit.

## Acknowledgements

- **Pygame**: A set of Python modules designed for writing video games, which was used to create the graphical interface of the game.
- This project was inspired by the classic Connect Four game.
