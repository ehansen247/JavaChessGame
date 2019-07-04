# JavaChessGame

## Introduction
A fully functional, two-player, graphics-based, interactive chess game/program.

To start the game...
1) git clone this repository (git clone https://github.com/ehansen247/JavaChessGame.git)
1) change into the project directory (cd JavaChessGame)
2) call the Chess.java main method (java Chess)

Thanks for playing!

### Specifications

	- Complies with all standard Chess rules as regulated by the World Chess Federation (FIDE)
		Ref: https://www.fide.com/

	- Features all standard Chess moves including pawn promotion, en-passant, castling and more!

	- Includes a user-defined timer (if desired). Possible game times range from 1 minute per 
	  player to ~two billion minutes per player!

	- Features elegantly designed Graphics, including 84 custom made pieces
          7 color choices, and a total of 42 possible color combinations!
	
	- Features fully functional and efficient Move Validity, Check, CheckMate and StaleMate detection
	
	- Features a GAME to PGN converter, output in a file named "LastGamePGN.out"
	  Fully complies with standard PGN format. Ref: https://en.wikipedia.org/wiki/Portable_Game_Notation
	  Example Output:
	   1. f3 e5
	   2. g4 Qh4#
	   1-0
	  
	
### Different Outputs
Outputs in the prompt window include:

  - "Not A Piece": The user has clicked a square before clicking a piece. Click a piece instead.   
  - "Out of Bounds": The user has clicked outside of the board.    
  - "Invalid Move": This move is invalid according to the rules of chess.   
  - "Wrong Color": It's not the color/player's turn. You cannot move the black pieces when it is not black's turn.   
  - "White/Black Wins!": The game has ended by checkmate.    
  - "White/Black wins on time!": The game has ended on time.    


### Contact
Contact me at ehansen247@gmail.com if you have any more questions.
