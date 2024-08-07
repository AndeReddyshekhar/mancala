# mancala
a console game to improve IQ
Game Flow:
The player selects a pit to move seeds from using the arrow keys and confirms the move with Enter.
The program handles the move logic, checks for captures, and determines if the player gets another move.
The opponent then makes a move.
This alternates until one side of the board is empty, after which the remaining seeds are moved to the stores and the game ends.
The game displays the final score and asks if the player wants to play again or quit.
Key Concepts:
State Machine: The game uses a state machine pattern to manage the different phases of the game.
User Input: The game relies heavily on user input via the console to control game actions.
Console Rendering: The board is rendered using ASCII characters to visualize the pits, stores, and seed counts.
