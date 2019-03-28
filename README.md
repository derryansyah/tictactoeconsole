TIC TAC TOE GAME

1. Migrating procedural code (global functions and variables) to OOP
2. Change playing mode to Player Vs Computer
3. Player can choose dimension of board start from 3X3 , 4X4, 5x5 ... etc
3. Player can choose as X (cross) or O(nought) when playing
4. Player can choose the Computer difficulty :
   - Easy : Computer AI uses a random algorithm to select a position o n the board.
			If random position already contains a marker, different random position is generated and the marker is placed if available.
   - Medium : Computer AI checks for 4 cases before generating a random position to place
				- Case A: Checks a possibility to win by placing the next marker in a row
				- Case B: Checks a possibility to win by placing the next marker in a column
				- Case C: Checks a possibility to win by placing the next marker in the left-top to right-bottom diagonal (\)
				- Case D: Checks a possibility to win by placing the next marker in the right-top to left-bottom diagonal (/)
   - Hard : Computer AI checks for 8 different cases.
			4 to check posibility to win in the next move and 4 to block the users winning scenario.
			If none of the cases satisfy the maker is placed at a randomly choosen position

Execution steps:
    tictactoe.java is the program to be executed
