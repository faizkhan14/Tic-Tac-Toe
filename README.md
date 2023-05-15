# Tic-Tac-Toe
The TicTacToe game is a classic two-player game where players take turns marking spaces on a 3x3 grid. The objective is to get three marks in a row, either horizontally, vertically, or diagonally, before the opponent does.
# Implementation
The game is implemented using Java programming language. The game board is represented as an array of Strings, with each element representing a slot on the board. The whoIsWinner method checks for a winner by comparing each row, column, and diagonal of the board. The showBoard method displays the current state of the board. The game loop continues until a winner is declared or the game ends in a tie.
# Rules
1- The game is played on a 3x3 grid.
2- Player 1 is 'X' and Player 2 is 'O'.
3- Players take turns entering the position they want to mark on the grid (1-9).
4- The game checks for a winner after each move.
5- If a player gets three marks in a row, they win the game.
6-If all positions are filled and no player has won, the game is a tie.
