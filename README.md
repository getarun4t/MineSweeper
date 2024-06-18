# MineSweeper
Minesweeper is a classic single-player puzzle game that requires both logic and strategy. The objective is to clear a rectangular board containing hidden mines without detonating any of them, with help from clues about the number of neighboring mines in each field.

## Rules of Minesweeper

1. **Game Board:**
   - The game board consists of a grid of covered cells, each of which may hide a mine.
   - The size of the grid and the number of mines are specified at the start of the game. Common sizes are 8x8, 16x16, and 30x16 grids, with varying mine counts.

2. **Uncovering Cells:**
   - Click on a cell to uncover it. If the cell contains a mine, the game ends and you lose.
   - If the cell does not contain a mine, it will reveal a number indicating how many mines are in the adjacent cells (including diagonals). If there are no mines in the adjacent cells, it will be blank (an empty space) and will automatically uncover all adjacent cells recursively.

3. **Marking Mines:**
   - Right-click (or use a flagging mechanism) on cells you suspect to contain mines to mark them with a flag. This helps keep track of potential mine locations and aids in logical deduction.

4. **Winning the Game:**
   - The game is won when all non-mine cells are uncovered. Flags do not need to be correctly placed for a win; only all safe cells need to be revealed.

5. **Losing the Game:**
   - The game is lost if a mine is uncovered by clicking on it.

6. **Numbers on the Board:**
   - Each number indicates the count of mines in the adjacent cells. For example, if a cell shows '3', there are three mines in the eight surrounding cells.

## Strategy and Tips

1. **First Move:**
   - The first click is always safe; typically, the game ensures that the first cell uncovered does not contain a mine.

2. **Corner Cells:**
   - Corners and edges are good starting points because they have fewer adjacent cells and are easier to deduce.

3. **Logical Deduction:**
   - Use the numbers to logically deduce where mines must be. For example, if a '1' is next to a covered cell and no other cells, that covered cell must be a mine.

4. **Flagging:**
   - Flag cells that you are certain contain mines to avoid accidentally clicking on them.

5. **Clearing Large Areas:**
   - If you uncover a blank cell (one with no adjacent mines), it can help clear large areas of the board automatically.



