tetris
======
You can find additional information about Tetris on Wikipedia at http://en.wikipedia.org/wiki/Tetris.

Acknowledgement: this project is an updated version of a Python programming assignment from MIT. The original project, on which this assignment is based, is available at:

http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/assignments/MIT6_189IAP11_final_proj.pdf

Game Play


The goal of the project is to implement the basic game play described below.

The game starts with an empty board drawn. The board is typically 10x20 squares. The top left corner square of the board has coordinates (0, 0) and the bottom right corner square has coordinates (9, 19) (the y-axis is flipped). A randomly chosen Tetris piece from the seven possible shapes is drawn at the top of the board. The piece starts falling at regular intervals – one square at a time.

Basic Rules


1.   The piece cannot fall into a square occupied by another piece or beyond the edge of the board.
2.   When a piece hits another piece or the bottom of the board, it stops moving and a new piece appears at the top of the board. 
3.   As the pieces fill up the board lines form. If a complete line forms, it disappears and all the blocks above it fall down one line.
4.   If a new piece can no longer be placed at the top of the board, the game ends and a “Game
Over!” message is displayed.

User Interaction


The user can use the arrow keys to move and rotate the pieces – ‘Left’, ‘Right’, ‘Down’ arrow keys move the piece left, right and down by 1 square respectively. The ‘Up’ arrow key will rotate the piece. The user can also drop a piece by pressing the spacebar. Dropping a piece means that the piece will fall down
until it can no longer move and the user can no longer rotate or move it in any other direction. When the piece is moved or rotated, it cannot move into another piece or over the edge of the board.

Project Design


1. Tetris Classes Overview

Take a look at the tetris_template.py file. It contains class definitions for:

•    Block – A single square on the board
•    Shape – A superclass (has subclasses for each individual type of shape)
•    Board – Implements functionality of the Tetris board.
•    Tetris – The Game controller
•    TetrisWin – Physical graphics window for Tetris. 

2. Creating a random shape

3. Keyboard Events

4. Moving Shapes

5. Attention! Piece overboard!

6. Adding a piece to the board

7. Attention! Intruders!

8. Rotating a piece

9. Automatically moving pieces

11. Game Over

CONGRATULATIONS! You now have your very own Tetris game.
