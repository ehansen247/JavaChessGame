# JavaChessGame

## Introduction
This is a Java Applet that simulates a two-player chess game. Upon starting the game, ***by calling the main method in the Chess class***, players have the option to choose the color of their game board and how much time each player will receive. The game ends when one player achieves checkmate or one player's timer hits zero. When the game ends, the players will no longer be able to move pieces. In the prompt window (the terminal window), hints and notes will be output to help the players navigate the board and know when the game concludes. When the board pops up, this window may be covered but make sure to move the prompt window back into view.

### Different Outputs
Outputs in the prompt window include:
Not A Piece: The user has clicked a square before clicking a piece. Click a piece instead.
Out of Bounds: The user has clicked outside of the board. 
Invalid Move: This move is invalid according to the rules of chess.
Wrong Color: It's the the color/player's turn. You cannot move the black pieces when it is not black's turn.
White/Black Wins!: The game has ended by checkmate. 
White/Black wins on time!: The game has ended on time. 

### PGN File
The most recently played game will be written in PGN notation (e.g. 1. e4 e5) and output to a file titled "LastGamePGN.txt." You can open this file and copy the PGN so that you can recreate and analyze your past games. 

### Running the Program
This project was created in BlueJ. To run from the command line (Terminal on Mac), change into the project directory and enter "java Chess." This will call the project's main method. 

### Contact
Contact me at ehansen247@gmail.com if you have any more questions.
