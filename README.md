# Minesweeper
Project 2 of CS 141: Minesweeper

Instructions for Minesweeper Game:

1. **Game Initialization**:
   - The game field will be automatically initialized with a specified number of mines.
   - The field is represented as a grid where each cell can be either a mine or safe.

2. **Command Format**:

   You can enter commands in the format: 
     - `rXY` to reveal a cell at row X and column Y (e.g., `r01` reveals the cell at row 0, column 1).
     - `fXY` to flag a cell as a suspected mine (e.g., `f13` flags the cell at row 1, column 3).
     - `uXY` to unflag a cell (e.g., `u42` unflags the cell at row 4, column 2).

4. **Gameplay**:
   - To start the game, simply run the program.
   - You will see the initial state of the field, which will display unknown cells.
   - Enter your command as specified above and press `Enter`.

5. **Objective**:
   - The goal is to reveal all safe cells without hitting any mines.
   - Flagging mines is optional but can help keep track of suspected mine locations.

6. **Game Over**:
   - If you reveal a mine, the game will end, and you will see a sad face. 
   - If you reveal all safe cells, you will see a happy face, indicating victory.

7. **Additional Notes**:
   - The game keeps track of the number of incorrectly flagged mines.
   - At any point, you can check how many mines are left by looking at the prompt that appears after each command.

Have fun playing!
