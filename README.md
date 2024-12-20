## Sliding Tile Puzzle Game

A classic sliding tile puzzle game where the goal is to arrange numbered tiles in order by moving a blank space. The game is implemented in Python.

### How to Play
1. **Objective**:
   - Arrange the tiles in ascending order from 1 to 15, with the blank space at the bottom-right corner.

2. **Controls**:
   - Use the following keys to move the blank space:
     - `W`: Move up
     - `A`: Move left
     - `S`: Move down
     - `D`: Move right
   - Type `QUIT` to exit the game at any time.

3. **Rules**:
   - You can only move the blank space into an adjacent tile's position.
   - Arrange the tiles to match this goal:
     ```
     1   2   3   4
     5   6   7   8
     9  10  11  12
    13  14  15    
     ```

4. **Start the Game**:
   - After running the program, press Enter to begin.
   - Tiles will start shuffled, and you can move them using the above controls.

5. **Winning**:
   - Once all tiles are arranged in the correct order, the game displays a congratulatory message.

---

### Setup Instructions

1. **Prerequisites**:
   - Python 3.7 or higher installed on your system.
   - A text editor or IDE (e.g., VS Code, PyCharm, or any preferred editor).

2. **Clone the Repository**:
   - Use the following command to clone the repository:
     ```bash
     git clone https://github.com/your-username/sliding-tile-puzzle.git
     ```
   - Navigate to the folder:
     ```bash
     cd sliding-tile-puzzle
     ```

3. **Run the Game**:
   - Execute the program in your terminal:
     ```bash
     python sliding_tile_puzzle.py
     ```

---

### Features
- Classic 4x4 sliding tile puzzle.
- Randomized starting positions for tiles.
- Easy-to-use controls (`WASD`).
- User-friendly interface in the terminal.

---

### Contribution
Feel free to contribute to this project by:
- Adding new features.
- Improving the UI.
- Enhancing gameplay mechanics.

---

### Sample Output
```plaintext
Sliding Tile Puzzle, by Faarah
    Use the WASD keys to move the tiles back to their original order:
                   1  2  3  4
                   5  6  7  8
                   9  10 11 12
                   13 14 15   
Press Enter to begin...

    +------+------+------+------+
    |  13  |   5  |  10  |   7  |
    +------+------+------+------+
    |   2  |   1  |   3  |   4  |
    +------+------+------+------+
    |      |  15  |  14  |   8  |
    +------+------+------+------+
    |  12  |   6  |   9  |  11  |
    +------+------+------+------+
Enter WASD (or QUIT): (A) (S) (D)
