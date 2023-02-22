# Reversi---Othello
HMTL-Javascript
This code is a JavaScript implementation of the Reversi game (also known as Othello) that can be played on an HTML canvas. The code defines several functions to draw the board and the game pieces, as well as to handle the game mechanics such as placing a piece and flipping the opponent's pieces.

The init() function initializes the canvas, sets up the game board, and draws the initial state of the game board. The drawBoard() function is called by init() to draw the board and game pieces. The startGame() function sets up the initial state of the game and displays a message telling the player to make the first move.

The putDiscPlayer(event) function is called when the user clicks on a cell in the game board. It determines which cell was clicked based on the position of the mouse pointer, and then calls the putDisc() function to place a game piece in that cell.

The putDisc() function places a game piece in the specified cell, checks if any of the opponent's pieces need to be flipped, and changes the player's turn to the next player.

The code also defines several helper functions, such as checkDisc() to check if a cell is valid for placing a game piece, and flipDisc() to flip the opponent's pieces when a piece is placed.

Overall, this code provides a functional implementation of the Reversi game that can be played in a web browser using an HTML canvas.
