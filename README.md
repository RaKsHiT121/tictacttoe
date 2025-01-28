Tic Tac Toe (GUI-based)

This project is a graphical implementation of the classic Tic Tac Toe game in Java using the Swing library. The game features a user-friendly interface where two players can play alternately. The GUI includes a top panel displaying the current player's turn and the game's outcome, along with an option to restart the game after it ends.

Features

Interactive GUI: The game board is displayed as a 3x3 grid of buttons for easy interaction.

Player Turn Display: The top panel updates dynamically to indicate whose turn it is (X or O).

Game Outcome Notification: After the game ends, it announces whether X wins, O wins, or if it's a tie.

Restart Option: After the game ends, players can choose to restart or exit the game.

Responsive Design: Buttons are appropriately sized, and all text is bold for better visibility.

How to Play

Start the Game:

Run the program to open the game window.

Make Moves:

Players X and O take turns clicking on an empty cell in the 3x3 grid.

Win Conditions:

A player wins by placing three of their marks (X or O) in a horizontal, vertical, or diagonal line.

Tie Condition:

The game ends in a tie if all cells are filled and no player has won.

Restart or Exit:

After the game ends, a dialog box appears asking if players want to play again or exit the game.

Installation and Setup

Prerequisites:

Ensure you have Java installed on your system.

Run the Game:

Compile the TicTacToeGUI.java file using the javac command:

javac TicTacToeGUI.java

Run the compiled program using the java command:

java TicTacToeGUI

Code Structure

Main Class: TicTacToeGUI

Initializes the game window, board, and status label.

Handles the logic for player turns, checking win conditions, and restarting the game.

ButtonClickListener: An inner class that listens for button clicks and updates the game state accordingly.

Customization

Button Size and Font:

The button size and font can be adjusted in the initialize() method.

buttons[i][j].setPreferredSize(new Dimension(80, 80));
buttons[i][j].setFont(new Font("Arial", Font.BOLD, 30));

Status Label Font:

Modify the font size or style for the status label in the constructor:

statusLabel.setFont(new Font("Arial", Font.BOLD, 20));

Future Enhancements

Add an AI opponent for single-player mode.

Highlight the winning line when a player wins.

Provide theme options for customization.

Screenshots

Initial State: Displays the empty board and indicates that it's X's turn.

Gameplay: Updates the board as players take their turns.

Game Over: Shows the winner or a tie and offers the option to restart or exit.

License

This project is open-source and available under the MIT License.

Acknowledgements

Developed using the Java Swing library for GUI components.

Enjoy playing Tic Tac Toe!

