Game of Life

---Assumptions---
- The game only ends when the user ends the game by quitting or starting a new game
- Other than this, I have made no additional assumptions outside of the given instructions.
Within the architecture of the game, the grid world is infinite, although there would eventually be an error
if a cell moves far enough off of the screen, depending on the available memory.

---Gameplay---
- Run the game by running game.py
- Instructions are printed in the command line
- Left-click on squares to add/remove cells to choose the initial configuration
- The game starts when the user presses the 'enter' key
- The user can scroll around the grid world at any time using the keyboard arrows
- The user can zoom in and out by pressing the 'p' and 'm' keys
- Press the 'enter' key during a game to end that game and begin a new one

---Requirements---
- Python 3
- Pygame 1.9.4