# Tic-Tac-Toe Game

Welcome to the Tic-Tac-Toe game! This Python program allows two players to play the classic game of Tic-Tac-Toe on the command line.

## How to Play

1. Run the Python program in your preferred Python interpreter.

2. The game starts by asking each player to choose their markers. Enter your desired markers (single characters) when prompted.

3. A random player is chosen to take the first turn. The player's marker is displayed on the board.

4. Confirm your readiness to play by entering "Yes" or "No."

5. During your turn, the game board will be displayed, and you need to enter the position where you want to place your marker. Positions are numbered from 1 to 9, representing the board layout as follows:

    ```
    1 | 2 | 3
    ---------
    4 | 5 | 6
    ---------
    7 | 8 | 9
    ```

6. The game continues alternating turns between Player 1 and Player 2.

7. The first player to get three of their markers in a row (horizontally, vertically, or diagonally) wins the game. If no player achieves this and all positions on the board are filled, the game ends in a draw.

8. After each game, you will be asked if you want to play again. Enter "Yes" to play another round or "No" to exit the game.

## Code Overview

The code is organized as follows:

- `player_input()`: This function lets players choose their markers.

- `choose_first()`: Randomly selects the player who goes first.

- `display_board(board)`: Displays the current game board.

- `player_choice(board)`: Prompts the current player to select a position for their marker.

- `place_marker(board, marker, position)`: Places a player's marker on the board.

- `win_check(board, marker)`: Checks if a player has won the game.

- `full_board_check(board)`: Checks if the game board is full.

- `replay()`: Asks if players want to play another round.

## Enjoy the Game!

Have fun playing Tic-Tac-Toe with a friend using this Python program! Experience the thrill of strategy and competition as you strive to outmaneuver your opponent and achieve victory. If you encounter any issues or have suggestions for improvement, feel free to reach out and let us know. Happy gaming!
