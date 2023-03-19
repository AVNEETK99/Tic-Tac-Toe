# Tic-Tac-Toe

This is a simple implementation of the Tic Tac Toe game using Python. The game can be played between two players who take turns to fill a 3x3 grid with their respective symbols ('X' or 'O'). The player who succeeds in placing three of their symbols in a horizontal, vertical, or diagonal row wins the game. If all the boxes in the grid are filled without any player winning, then the game is considered to be a draw.

## Instructions to run the game
* Make sure you have Python installed on your machine.
* Clone the repository or download the tictactoe.py file.
* Navigate to the directory containing the tictactoe.py file using the terminal or command prompt.
* Run the following command to start the game:
``` python tictactoe.py ```


## Functionality of the code
The code consists of several functions to print the Tic Tac Toe grid, print the scoreboard, check if any player has won, and check if the game is drawn. The main game loop is implemented in the single_game() function. Here is a brief description of each function:

* print_tic_tac_toe(values): This function takes a list values as input which represents the state of the grid. It prints the Tic Tac Toe grid to the console.

* print_scoreboard(score_board): This function takes a dictionary score_board as input which stores the scores of the players. It prints the current score to the console.

* check_win(player_pos, cur_player): This function takes a dictionary player_pos as input which stores the positions occupied by the players and the current player cur_player. It checks if the current player has won the game.

* check_draw(player_pos): This function takes a dictionary player_pos as input which stores the positions occupied by the players. It checks if the game has ended in a draw.

* single_game(cur_player): This function takes the current player cur_player as input and implements a single game of Tic Tac Toe.

* The main function checks for player names, their choices for symbols, and starts a series of Tic Tac Toe games. The loop runs until the players quit.
