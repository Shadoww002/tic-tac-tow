### **Tic Tac Toe Game in Python**

This is a command-line implementation of the classic Tic Tac Toe game, where two players take turns marking spaces on a 3x3 grid. The objective is to align three of your marks (either "X" or "O") horizontally, vertically, or diagonally before your opponent does.

### **Features**

-**Player Choice:** Player 1 selects their mark (X or O), and Player 2 automatically gets the other.
-**Input Validation:** Ensuresplayers choose valid options and positions on the grid.
-**Dynamic Board Display:** The game board updates in real-time after each move.
-**Win/Draw Detection:** Detects when a player wins or when the match ends in a draw.
-**Replay Option:** Players can replay the game as many times as they wish.

### How to Play

- Run the Python script in your terminal or any Python IDE.
- Player 1 is prompted to choose either "X" or "O" as their mark.
- Players take turns entering a position (1-9) on the grid:

 1 | 2 | 3
 ---------
 4 | 5 | 6
 ---------
 7 | 8 | 9

- The game announces the winner or a draw when applicable.
- Players can choose to play again or exit the game.

### Requirements

- Python 3.x installed on your system.
- Running the Game
- Clone or download the script.
- Open your terminal or IDE and run the script:
- bash
- Copy
- Edit
- python tic_tac_toe.py
- Follow the on-screen prompts to play.

### Code  Overview

**Functions**

- **display(board):** Displays the current state of the game board.
- **choice():** Allows Player 1 to choose their mark (X or O).
- **Player_Position(Player):** Prompts the player to select a valid position on the board.
- **win_check(board, choice):** Checks if a player has won.
- **space_check(board):** Checks if any positions are still available.
- **game_update(board, Position, choice):** Updates the board with the player's choice if the position is unoccupied.
- **replay():** Prompts players to replay the game or exit.
- **game():** The main game loop that ties all the functions together.

### Customization

- Modify the game board size or winning conditions by adjusting the win_check() and board logic.
- Add features like a computer AI to play against a single player.

### License

This project is open-source and free to use. Feel free to modify or improve it!

Enjoy the game! 😊
