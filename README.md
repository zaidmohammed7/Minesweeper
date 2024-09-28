# Minesweeper

## Project 2 of CS 141: Minesweeper

### Instructions for Playing Minesweeper:

1. **Game Initialization**:
   - The game field initializes automatically with a predetermined number of mines.
   - Each cell in the grid is either a mine or safe.

2. **Command Format**:

   Enter commands in the following format:
     - `rXY`: Reveal the cell at row X and column Y (e.g., `r01` reveals the cell at row 0, column 1).
     - `fXY`: Flag a cell as a suspected mine (e.g., `f13` flags the cell at row 1, column 3).
     - `uXY`: Unflag a cell (e.g., `u42` unflags the cell at row 4, column 2).

4. **Gameplay**:
   - To start the game, run the program.
   - The initial state of the field will display unknown cells.
   - Enter your command as specified above and press `Enter`.

5. **Objective**:
   - Your goal is to reveal all safe cells without hitting any mines.
   - Flagging mines is optional, but it can help you track suspected mine locations.

6. **Game Over**:
   - Revealing a mine ends the game with a sad face.
   - Revealing all safe cells results in a happy face, indicating victory!

7. **Additional Notes**:
   - The game tracks the number of incorrectly flagged mines.
   - After each command, you can check how many mines are left at the prompt.

### Have Fun Playing!
