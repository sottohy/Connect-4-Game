# Connect 4 with Minimax and Alpha-Beta Pruning

A Python implementation of Connect 4 using the Pygame library. The game includes both Minimax and Alpha-Beta Pruning algorithms for the computer player, with three difficulty levels: Easy, Medium, and Hard.

## Features
- Classic Connect 4 Gameplay: Play against the computer in a standard 6x7 Connect 4 grid.
- Two AI Algorithms: Choose between the Minimax and Alpha-Beta Pruning algorithms for the computer opponent.
- Difficulty Levels: Select from Easy, Medium, and Hard difficulty levels for a more challenging game.
- Visual Interface: Interactive game board with Pygame.
  
## Requirements
- Python 3.x
- Pygame library

## Installation
1. Install Python 3.x from python.org.
2. Install Pygame using pip:
   ```
   pip install pygame
   ```

  ## Usage
1. Clone the repository or download the script.
1. Run the script using Python:
   ```
   python connect4.py
   ```

## How to Play
1. Start the Game: The game window will open with a prompt to choose the AI algorithm.
2. Choose an Algorithm: Click on either the "Minimax" or "Alpha Beta" button to select the AI algorithm.
3. Select Difficulty: Choose the difficulty level by clicking on "Easy," "Medium," or "Hard."
4. Play: Drop your pieces into the columns by clicking on the desired column. The goal is to connect four of your pieces in a row horizontally, vertically, or diagonally.
5. AI Turn: The computer will make its move using the selected algorithm and difficulty level.


## Game Controls
- Mouse Click: Click on a column to drop your piece.
- Quit: Close the game window to exit

## Initialization
Colors and Dimensions: Defines colors, board dimensions, and cell sizes.
Pygame Initialization: Sets up the Pygame window and caption.
Board Initialization: Creates the game board as a 6x7 grid.

## Functions
- draw_board(board): Draws the game board and pieces on the screen.
- drop_piece(board, row, column, piece): Drops a game piece in the specified column.
- is_valid_location(board, column): Checks if a column is a valid location for dropping a piece.
- GetValidLocations(board): Returns a list of valid columns for dropping pieces.
- FirstValidRow(board, col): Finds the first available row in the specified column.
- IsGameOver(board): Checks if the game is over (win condition or draw).
- evaluate_window(window, piece): Evaluates the score of a window (subset of the board) for the specified piece.
- score_position(board, piece): Calculates the score for the current board position.
- Minimax(board, depth, MaxPlayer): Implements the Minimax algorithm.
- MinimaxAlphaBeta(board, depth, alpha, beta, MaxPlayer): Implements the Alpha-Beta Pruning algorithm.
- run_game(board): Main function to run the game, handle user inputs, and execute the game loop.


# Game Interface
![Screenshot (2400)](https://github.com/sottohy/Connect-4-game/assets/91037437/25be0067-2cc7-46be-9e0a-6776affb2bb1)
