README for Tic-Tac-Toe Game


Introduction

This is a Python implementation of the Tic-Tac-Toe game that allows two players to play against each other. It uses a 3x3 board to represent the game.


Prerequisites

To play this game, you need to have Python installed on your system.


How to Play

The game starts by creating a 3x3 empty board. Each cell of the board is represented by a '-' character.

The first player is selected randomly.

The players take turns to place their marker ('X' or 'O') on an empty cell of the board. The player who places three of their markers in a horizontal, vertical, or diagonal row wins the game.

If all cells are filled with markers and no player has three in a row, the game ends in a draw.


How to Run the Game

Open a terminal or command prompt window.

Navigate to the directory where the TicTacToe.py file is saved.

Type 'python TicTacToe.py' and press Enter to start the game.


Code Structure

The code is structured in a single Python file, TicTacToe.py, which contains the following:

A class called TicTacToe, which represents the game.

The TicTacToe class has the following methods:

create_board(): creates an empty 3x3 board.

get_random_first_player(): randomly selects the first player.

fix_spot(row, col, player): fixes the spot with the given row and column number by placing the marker of the current player.

is_player_win(player): checks if the current player has won the game.

is_board_filled(): checks if the board is completely filled.

swap_player_turn(player): swaps the turn between players.

show_board(): displays the current state of the board.

start(): starts the game by calling the above methods in a loop until the game ends.

The TicTacToe class is instantiated and the game is started by calling the start() method at the end of the file.


Conclusion

This Tic-Tac-Toe game is a fun and simple game to play between two players. By following the steps mentioned above, you can easily run the game and enjoy playing with your friends.