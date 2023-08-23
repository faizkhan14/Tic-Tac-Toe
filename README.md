## Tic Tac Toe

### Introduction

Tic Tac Toe is a classic game that can be enjoyed by people of all ages. This game is a simple and fun way to test your logic and strategy skills. The objective of the game is to get three of your marks in a row, either horizontally, vertically, or diagonally. The first player to do so wins the game.

### Code Explanation

The code for this game is written in Java. The code is well-commented and easy to understand. The main class is called `TicTacToe`. This class contains the main method, which is the entry point of the program.

The `TicTacToe` class has several instance variables. These variables store the state of the game, such as the current player, the game board, and the winner.

The `TicTacToe` class also has several methods. These methods perform various tasks, such as displaying the game board, getting the player's input, and checking for a winner.

The game board is represented by a 3x3 array of strings. Each element in the array represents a square on the game board. The value of each element can be either "X", "O", or a number from 1 to 9. The numbers represent the squares on the game board, as shown below:

```
1 | 2 | 3
4 | 5 | 6
7 | 8 | 9
```

The current player is represented by a string variable called `player`. The value of this variable can be either "X" or "O".

The winner is represented by a string variable called `winner`. The value of this variable can be either "X", "O", or "Tie".

The `showBoard()` method displays the game board to the console. The method loops through the game board array and prints the value of each element.

The `getInput()` method gets the player's input. The method prompts the player to enter a number from 1 to 9. The method then returns the player's input.

The `checkWinner()` method checks for a winner. The method loops through the game board array and checks for three consecutive "X"s or "O"s. If the method finds three consecutive "X"s or "O"s, it returns the winner. Otherwise, the method returns null.

The `main()` method is the entry point of the program. The method creates a new instance of the `TicTacToe
