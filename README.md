# battle 

This code represents a simplified console-based Battleship game implemented in C#. The game is played on a 10x10 grid where the player's goal is to sink five hidden ships (represented by 'X' on the grid) by guessing their locations. Here's a brief description of the code:
1. The grid is a 10x10 character array used to represent the game board.
2. The remainingShips variable keeps track of the number of ships that are yet to be sunk. The game continues until all five ships are sunk.
3. The InitializeGrid function initializes the grid with empty spaces.
4. The PlaceShips function randomly places five ships on the grid.
5. The DisplayGrid function displays the current state of the game board, showing the grid with coordinates and marking hits and misses.
6. The PlayTurn function allows the player to input their guesses for the row and column. It checks if the input coordinates are valid and processes the guess, updating the grid accordingly.
7. The game continues in a loop, allowing the player to take turns until all ships are sunk. The player wins when all five ships have been successfully hit and sunk.

This code provides a basic example of a Battleship game and can serve as a starting point for building a more feature-rich version with additional gameplay elements.


 
